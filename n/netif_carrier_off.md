# Function: <code>netif_carrier_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817412b0)
Location: net/sched/sch_generic.c:366
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817412b0-ffffffff817412d6: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817ae160)
Location: net/sched/sch_generic.c:379
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817ae160-ffffffff817ae187: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817dd7f0)
Location: net/sched/sch_generic.c:379
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817dd7f0-ffffffff817dd817: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fce20)
Location: net/sched/sch_generic.c:379
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
```
**Symbols:**

```
ffffffff817fce20-ffffffff817fce47: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187a580)
Location: net/sched/sch_generic.c:386
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
```
**Symbols:**

```
ffffffff8187a580-ffffffff8187a5a7: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cbd70)
Location: net/sched/sch_generic.c:524
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
```
**Symbols:**

```
ffffffff818cbd70-ffffffff818cbd9b: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f7210)
Location: net/sched/sch_generic.c:524
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
```
**Symbols:**

```
ffffffff818f7210-ffffffff818f723b: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81956920)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81956920-ffffffff8195694a: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198cdc0)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff8198cdc0-ffffffff8198cdea: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a64630)
Location: net/sched/sch_generic.c:507
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81a64630-ffffffff81a6465a: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6c770)
Location: net/sched/sch_generic.c:507
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81a6c770-ffffffff81a6c79a: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a54f00)
Location: net/sched/sch_generic.c:532
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81a54f00-ffffffff81a54f2a: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0dc10)
Location: net/sched/sch_generic.c:542
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81b0dc10-ffffffff81b0dc3a: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c94ff0)
Location: net/sched/sch_generic.c:597
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down
```
**Symbols:**

```
ffffffff81c94ff0-ffffffff81c95026: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e50ad0)
Location: net/sched/sch_generic.c:594
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down
```
**Symbols:**

```
ffffffff81e50ad0-ffffffff81e50b06: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eac2e0)
Location: net/sched/sch_generic.c:594
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/net_failover.c:net_failover_create
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down
```
**Symbols:**

```
ffffffff81eac2e0-ffffffff81eac316: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f6ed70)
Location: net/sched/sch_generic.c:595
Inline: True
Direct callers:
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_close
  - drivers/net/netkit.c:netkit_close
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/net_failover.c:net_failover_create
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down
```
**Symbols:**

```
ffffffff81f6ed70-ffffffff81f6eda9: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c37fa8)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/mii.c:mii_check_link
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_close
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffff800010c37fa8-ffff800010c38054: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4aa18)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_stop
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_adjust_link
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
c0d4aa18-c0d4aa78: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d301c0)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
c000000000d301c0-c000000000d3023c: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007a97b8)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffe0007a97b8-ffffffe0007a980a: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192cc30)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff8192cc30-ffffffff8192cc5a: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e6730)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff818e6730-ffffffff818e675a: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197ddc0)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff8197ddc0-ffffffff8197ddea: netif_carrier_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_off(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a06f0)
Location: net/sched/sch_generic.c:511
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:netfront_probe
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff819a06f0-ffffffff819a071a: netif_carrier_off (STB_GLOBAL)
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
