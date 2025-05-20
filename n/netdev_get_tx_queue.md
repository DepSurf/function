# Function: <code>netdev_get_tx_queue</code>

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
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:1906
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff815f253f)
Location: include/linux/netdevice.h:1906
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:1906
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff815faaac)
Location: include/linux/netdevice.h:1906
Inline: True
```
```
In net/core/dev.c (ffffffff81719005)
Location: include/linux/netdevice.h:1906
Inline: True
Inline callers:
  - net/core/dev.c:netif_wake_subqueue
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:1906
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738cfb)
Location: include/linux/netdevice.h:1906
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81741026)
Location: include/linux/netdevice.h:1906
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_mq.c (ffffffff8174201f)
Location: include/linux/netdevice.h:1906
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_graft
```
```
In net/sched/sch_api.c (0)
Location: include/linux/netdevice.h:1906
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:1906
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818037ac)
Location: include/linux/netdevice.h:1906
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/tun.c (ffffffff8164fbc8)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff816521ff)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:1946
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8165ade3)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81785472)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netif_wake_subqueue
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:1946
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a4fbb)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817aeb21)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff817af277)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_get
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff817b148a)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:1946
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818749ec)
Location: include/linux/netdevice.h:1946
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/tun.c (ffffffff81681d7e)
Location: include/linux/netdevice.h:1928
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:1928
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81688b56)
Location: include/linux/netdevice.h:1928
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff817b2a82)
Location: include/linux/netdevice.h:1928
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netif_wake_subqueue
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:1928
Inline: True
```
```
In net/core/netpoll.c (ffffffff817d3a2b)
Location: include/linux/netdevice.h:1928
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817de1a1)
Location: include/linux/netdevice.h:1928
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff817de8f7)
Location: include/linux/netdevice.h:1928
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_get
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff817e0c0a)
Location: include/linux/netdevice.h:1928
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:1928
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818a8f3e)
Location: include/linux/netdevice.h:1928
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/tun.c (ffffffff81696cf2)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:1952
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8169e34b)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff817d0282)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_reset_xps_queues
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:1952
Inline: True
```
```
In net/core/netpoll.c (ffffffff817f2d67)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817fd7f1)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff817fdf27)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_get
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff818000ee)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:1952
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818cf925)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/tun.c (ffffffff81701b8a)
Location: include/linux/netdevice.h:1968
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:1968
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817094ee)
Location: include/linux/netdevice.h:1968
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81849be5)
Location: include/linux/netdevice.h:1968
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_reset_xps_queues
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:1968
Inline: True
```
```
In net/core/netpoll.c (ffffffff8186eba7)
Location: include/linux/netdevice.h:1968
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8187b3de)
Location: include/linux/netdevice.h:1968
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff8187bb47)
Location: include/linux/netdevice.h:1968
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff8187de86)
Location: include/linux/netdevice.h:1968
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:1968
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81954898)
Location: include/linux/netdevice.h:1968
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In drivers/net/tun.c (ffffffff8173b708)
Location: include/linux/netdevice.h:2036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2036
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81747fc7)
Location: include/linux/netdevice.h:2036
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81893a5a)
Location: include/linux/netdevice.h:2036
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
```
```
In net/core/link_watch.c (ffffffff818ae2ea)
Location: include/linux/netdevice.h:2036
Inline: True
```
```
In net/core/netpoll.c (ffffffff818bf2f7)
Location: include/linux/netdevice.h:2036
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818cd88e)
Location: include/linux/netdevice.h:2036
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff818ce355)
Location: include/linux/netdevice.h:2036
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff818d0922)
Location: include/linux/netdevice.h:2036
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff8196e8cf)
Location: include/linux/netdevice.h:2036
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffff8175eec8)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2101
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8176c094)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818b4477)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffffffff818d256a)
Location: include/linux/netdevice.h:2101
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818e325d)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff818e8114)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818f8ace)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff818f94d5)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff818fbac1)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff819a4499)
Location: include/linux/netdevice.h:2101
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffff8179c5c5)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2090
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817a9ea0)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81900d97)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffffffff8191f81c)
Location: include/linux/netdevice.h:2090
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff819335cc)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81938354)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8195829e)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81958f6b)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff8195b41c)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81a10841)
Location: include/linux/netdevice.h:2090
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffff817c0075)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817cd908)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819330c7)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffffffff81951a5c)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff8196610c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff8196b214)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8198e74e)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff8198f40b)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81991a7c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81a47581)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffff8188b005)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818953b0)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff818994a3)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81a07f3b)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
```
In net/core/link_watch.c (ffffffff81a228ed)
Location: include/linux/netdevice.h:2188
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81a38a9a)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81a3e9c4)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a66502)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81a66d5b)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81a6b14a)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81b376e2)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In drivers/net/tun.c (ffffffff818991a5)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a3a94)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff818a79c6)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81a0962d)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
```
In net/core/link_watch.c (ffffffff81a22c4d)
Location: include/linux/netdevice.h:2252
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81a3b1ba)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81a41764)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a6e5e2)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81a6ed0b)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81a738d6)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81b46412)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In drivers/net/tun.c (ffffffff8187a5c5)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8188576f)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff8188b25b)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff819eff9d)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
```
In net/core/link_watch.c (ffffffff81a09f7d)
Location: include/linux/netdevice.h:2316
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81a22f00)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81a267f4)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a56e72)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81a575a3)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81a5c2c7)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81b34300)
Location: include/linux/netdevice.h:2316
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In drivers/net/tun.c (ffffffff81910ba4)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819170ff)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff8191f36a)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
  - drivers/net/xen-netfront.c:netfront_resume
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81aa13cd)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
```
In net/core/link_watch.c (ffffffff81abc47d)
Location: include/linux/netdevice.h:2336
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81ad7350)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81adb574)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81b0fca2)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81b104e3)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_change_real_num_tx
  - net/sched/sch_mq.c:mq_change_real_num_tx
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81b15477)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81bfa9b1)
Location: include/linux/netdevice.h:2336
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In drivers/net/tun.c (ffffffff81a6097f)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b4bf)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81a755c8)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81c192c0)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
```
In net/core/link_watch.c (ffffffff81c36f9f)
Location: include/linux/netdevice.h:2416
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81c57a6c)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81c5ca13)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81c94b5f)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81c977a3)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81c9c71b)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81d93d8a)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ioam6.c (ffffffff81dd7244)
Location: include/linux/netdevice.h:2416
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In drivers/net/tun.c (ffffffff81becf3c)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe35f)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81c07026)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81dca2c0)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
```
In net/core/link_watch.c (ffffffff81dea5cf)
Location: include/linux/netdevice.h:2443
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81e0d83c)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81e13113)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81e505cf)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81e53803)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81e58bdf)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81f624cf)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ioam6.c (ffffffff81fa8bff)
Location: include/linux/netdevice.h:2443
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In drivers/net/tun.c (ffffffff81c4543d)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff81c4d304)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_tx_timeout
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:skb_xmit_done
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c639b4)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c6fa)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/net/net_failover.c (ffffffff81c6fa6c)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (ffffffff81e3ae40)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
```
In net/core/link_watch.c (ffffffff81e5bdb2)
Location: include/linux/netdevice.h:2495
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81e80a8c)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81e86213)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81eabda4)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81eaf083)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81eb4788)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81fc22b8)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ioam6.c (ffffffff8200958f)
Location: include/linux/netdevice.h:2495
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In drivers/net/tun.c (ffffffff81cfad78)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff81d02e94)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_tx_timeout
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:skb_xmit_done
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a3d4)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81d210a6)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/net/net_failover.c (ffffffff81d2431c)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (ffffffff81eec70b)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/core/dev.c:netif_queue_set_napi
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_detach
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
```
In net/core/link_watch.c (ffffffff81f1b171)
Location: include/linux/netdevice.h:2554
Inline: True
```
```
In net/core/netdev-genl.c (ffffffff81f3d263)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
```
```
In net/core/net-sysfs.c (ffffffff81f41a49)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff81f48223)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81f6e841)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81f71b23)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81f77458)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff8208f833)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ioam6.c (ffffffff820d852f)
Location: include/linux/netdevice.h:2554
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In drivers/net/tun.c (ffff8000109db5a0)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e46b0)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea760)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
```
```
In drivers/net/ethernet/smsc/smc91x.c (0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In drivers/net/xen-netfront.c (ffff800010a09740)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffff800010bd10a4)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffff800010bf35f4)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (ffff800010c0b948)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffff800010c10ddc)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffff800010c3a070)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffff800010c3b2fc)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffff800010c3dd60)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffff800010d0a0f8)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (c0ac1ed4)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accba8)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad5bfc)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_adjust_link
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_handler
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0ada71c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_update_channels_res
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_resume_data_pass
```
```
In drivers/net/ppp/ppp_generic.c (c0adfb08)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (c0cebd50)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (c0d0bf98)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/netpoll.c (c0d28c24)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c0d4c2d8)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (c0d4d040)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (c0d5100c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (c0e107c4)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (c000000000a9c740)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aaa79c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (c000000000caf344)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (c000000000cd8a44)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (c000000000cf69c0)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (c000000000cfde9c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c000000000d330b0)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (c000000000d34320)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (c000000000d39ba0)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (c000000000e34938)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffe00062551a)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062e99c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/dev.c (ffffffe00075b698)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffffffe000774ff0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (ffffffe000788718)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffe00078da70)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffe0007ab280)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_trans_start
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffe0007abafc)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffe0007af14a)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffe000851cde)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffff81784b45)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81792528)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818d30c7)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffffffff818f1a2c)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff819060dc)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff8190b1e4)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8192e5be)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff8192f27b)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff819318ec)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff819e6c11)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffff81764495)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/dev.c (ffffffff8188cf57)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffffffff818ab86c)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818bff0c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff818c4fb7)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818e80be)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff818e8d7b)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff818eb3ec)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff819a39d1)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffff817b4ef5)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817c2788)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819240c7)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffffffff81942a5c)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff8195710c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff8195c214)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8197f74e)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff8198040b)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff81982a7c)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81a51691)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/net/tun.c (ffffffff817ceec5)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817dca48)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81945537)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_bind_sb_channel_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/link_watch.c (ffffffff8196435c)
Location: include/linux/netdevice.h:2120
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff819791ec)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
```
In net/core/netpoll.c (ffffffff8197dbc4)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff819a1cae)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff819a296b)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_init
```
```
In net/sched/sch_api.c (ffffffff819a4fbc)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/ipv6/addrconf.c (ffffffff81a5d5e1)
Location: include/linux/netdevice.h:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
</ul>

## Differences
