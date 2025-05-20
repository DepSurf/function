# Function: <code>netdev_priv</code>

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
In drivers/net/tun.c (ffffffff815f062d)
Location: include/linux/netdevice.h:1964
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/virtio_net.c (ffffffff815f209a)
Location: include/linux/netdevice.h:1964
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_probe
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f8991)
Location: include/linux/netdevice.h:1964
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff815fd1e7)
Location: include/linux/netdevice.h:1964
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:1964
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
In drivers/net/tun.c (ffffffff816506df)
Location: include/linux/netdevice.h:2041
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/virtio_net.c (ffffffff816542db)
Location: include/linux/netdevice.h:2041
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81655f06)
Location: include/linux/netdevice.h:2041
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8165d0fc)
Location: include/linux/netdevice.h:2041
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2041
Inline: True
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
In drivers/net/tun.c (ffffffff816823bf)
Location: include/linux/netdevice.h:2023
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81683be6)
Location: include/linux/netdevice.h:2023
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8168a4d7)
Location: include/linux/netdevice.h:2023
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2023
Inline: True
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
In drivers/net/tun.c (ffffffff81696646)
Location: include/linux/netdevice.h:2038
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816991a6)
Location: include/linux/netdevice.h:2038
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff816a015c)
Location: include/linux/netdevice.h:2038
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2038
Inline: True
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
In drivers/net/tun.c (ffffffff8170144d)
Location: include/linux/netdevice.h:2054
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81705bc2)
Location: include/linux/netdevice.h:2054
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8170b322)
Location: include/linux/netdevice.h:2054
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2054
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2054
Inline: True
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
In drivers/net/tun.c (ffffffff8173bda7)
Location: include/linux/netdevice.h:2122
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742125)
Location: include/linux/netdevice.h:2122
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81749d77)
Location: include/linux/netdevice.h:2122
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2122
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2122
Inline: True
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
In drivers/net/tun.c (ffffffff8175f6e7)
Location: include/linux/netdevice.h:2187
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81766235)
Location: include/linux/netdevice.h:2187
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8176df07)
Location: include/linux/netdevice.h:2187
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2187
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2187
Inline: True
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
In drivers/net/tun.c (ffffffff8179cf17)
Location: include/linux/netdevice.h:2178
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a3945)
Location: include/linux/netdevice.h:2178
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817ac121)
Location: include/linux/netdevice.h:2178
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2178
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2178
Inline: True
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
In drivers/net/tun.c (ffffffff817c09b7)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c7395)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817cfb61)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
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
In drivers/net/tun.c (ffffffff8188c02f)
Location: include/linux/netdevice.h:2276
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81891c95)
Location: include/linux/netdevice.h:2276
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8189a3c5)
Location: include/linux/netdevice.h:2276
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2276
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2276
Inline: True
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
In drivers/net/tun.c (ffffffff8189a48f)
Location: include/linux/netdevice.h:2363
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189ff65)
Location: include/linux/netdevice.h:2363
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff818a8395)
Location: include/linux/netdevice.h:2363
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2363
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2363
Inline: True
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
In drivers/net/tun.c (ffffffff8187ab67)
Location: include/linux/netdevice.h:2427
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882a75)
Location: include/linux/netdevice.h:2427
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8188b815)
Location: include/linux/netdevice.h:2427
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2427
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2427
Inline: True
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
In drivers/net/tun.c (ffffffff8190c067)
Location: include/linux/netdevice.h:2447
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914415)
Location: include/linux/netdevice.h:2447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/netdevice.h:2447
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8191f295)
Location: include/linux/netdevice.h:2447
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_uninit
```
```
In net/core/dev_ioctl.c (ffffffff81ad0c1b)
Location: include/linux/netdevice.h:2447
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2447
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2447
Inline: True
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
In drivers/net/tun.c (ffffffff81a5fa67)
Location: include/linux/netdevice.h:2525
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a699c5)
Location: include/linux/netdevice.h:2525
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/netdevice.h:2525
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81a73605)
Location: include/linux/netdevice.h:2525
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_uninit
```
```
In net/core/dev_ioctl.c (ffffffff81c4e3fd)
Location: include/linux/netdevice.h:2525
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2525
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2525
Inline: True
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
In drivers/net/tun.c (ffffffff81beaf57)
Location: include/linux/netdevice.h:2552
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc535)
Location: include/linux/netdevice.h:2552
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/netdevice.h:2552
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c07895)
Location: include/linux/netdevice.h:2552
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_uninit
```
```
In net/core/dev_ioctl.c (ffffffff81e033fc)
Location: include/linux/netdevice.h:2552
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2552
Inline: True
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
In drivers/net/tun.c (ffffffff81c43397)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/virtio_net.c (ffffffff81c519e7)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_features
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_rxnfc
  - drivers/net/virtio_net.c:virtnet_set_rxfh
  - drivers/net/virtio_net.c:virtnet_set_coalesce
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61bb5)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/netdevice.h:2605
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c6cfb5)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_uninit
```
```
In drivers/net/net_failover.c (0)
Location: include/linux/netdevice.h:2605
Inline: True
```
```
In net/core/dev_ioctl.c (ffffffff81e75cab)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2605
Inline: True
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
In drivers/net/netkit.c (0)
Location: include/linux/netdevice.h:2664
Inline: True
```
```
In drivers/net/tun.c (ffffffff81cf85c7)
Location: include/linux/netdevice.h:2664
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
```
In drivers/net/virtio_net.c (ffffffff81d07c7d)
Location: include/linux/netdevice.h:2664
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_features
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_rxnfc
  - drivers/net/virtio_net.c:virtnet_set_rxfh
  - drivers/net/virtio_net.c:virtnet_set_per_queue_coalesce
  - drivers/net/virtio_net.c:virtnet_set_coalesce
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d185a5)
Location: include/linux/netdevice.h:2664
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81d218f5)
Location: include/linux/netdevice.h:2664
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:xennet_uninit
```
```
In drivers/net/net_failover.c (0)
Location: include/linux/netdevice.h:2664
Inline: True
```
```
In net/core/dev_ioctl.c (ffffffff81f35c32)
Location: include/linux/netdevice.h:2664
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2664
Inline: True
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
In drivers/net/tun.c (ffff8000109daf0c)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e242c)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_alloc
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_adjust_link
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_get_ethtool_stats
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_set_mac_address
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_stop
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_interrupt
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_set_rx_mode
```
```
In drivers/net/ethernet/broadcom/bgmac-platform.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9eec)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109ffbe0)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffff800010a090e4)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
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
In drivers/net/tun.c (c0ac2144)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acb1e4)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad1ee8)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_pauseparam
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_xdp_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_adjust_link
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0adb1dc)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_channels_common
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_resume_data_pass
```
```
In drivers/net/ppp/ppp_generic.c (c0adc0d8)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
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
In drivers/net/tun.c (c000000000a9d7d8)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_free_netdev
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa6380)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
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
In drivers/net/tun.c (ffffffe000625ede)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062be90)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
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
In drivers/net/tun.c (ffffffff81785487)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178be75)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817947a1)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
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
In drivers/net/tun.c (ffffffff81764dd7)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/vxlan.c (ffffffff8176f73b)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_switchdev_event
  - drivers/net/vxlan.c:vxlan_switchdev_event
  - drivers/net/vxlan.c:vxlan_fdb_offloaded_set
  - drivers/net/vxlan.c:vxlan_dellink
  - drivers/net/vxlan.c:vxlan_changelink
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:__vxlan_dev_create
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_open
  - drivers/net/vxlan.c:vxlan_uninit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_snoop
  - drivers/net/vxlan.c:vxlan_fdb_get
  - drivers/net/vxlan.c:vxlan_fdb_dump
  - drivers/net/vxlan.c:vxlan_fdb_delete
  - drivers/net/vxlan.c:vxlan_fdb_add
  - drivers/net/vxlan.c:vxlan_fdb_find_uc
  - drivers/net/vxlan.c:vxlan_ip_miss
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81774c45)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/ipv4/ip_tunnel.c (ffffffff81968275)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_changelink
  - net/ipv4/ip_tunnel.c:ip_tunnel_newlink
  - net/ipv4/ip_tunnel.c:ip_tunnel_init_net
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ip_tunnel.c:ip_tunnel_lookup
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
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
In drivers/net/tun.c (ffffffff817b5837)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bc215)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817c49e1)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
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
In drivers/net/tun.c (ffffffff817cfbd7)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d6515)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817dec91)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/netdevice.h:2191
Inline: True
```
</details>
</li>
</ul>

## Differences
