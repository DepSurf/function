# Function: <code>netif_carrier_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81741800)
Location: net/sched/sch_generic.c:347
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81741800-ffffffff8174183f: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817ae690)
Location: net/sched/sch_generic.c:360
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff817ae690-ffffffff817ae6d0: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817ddd20)
Location: net/sched/sch_generic.c:360
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff817ddd20-ffffffff817ddd60: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fd340)
Location: net/sched/sch_generic.c:360
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
```
**Symbols:**

```
ffffffff817fd340-ffffffff817fd37c: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187ad90)
Location: net/sched/sch_generic.c:367
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
```
**Symbols:**

```
ffffffff8187ad90-ffffffff8187adcc: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cd130)
Location: net/sched/sch_generic.c:505
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
```
**Symbols:**

```
ffffffff818cd130-ffffffff818cd170: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f8490)
Location: net/sched/sch_generic.c:505
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
```
**Symbols:**

```
ffffffff818f8490-ffffffff818f84d0: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81957c30)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81957c30-ffffffff81957c74: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198e0d0)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff8198e0d0-ffffffff8198e114: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a645e0)
Location: net/sched/sch_generic.c:488
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/xen-netfront.c:xennet_connect
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81a645e0-ffffffff81a64626: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6c720)
Location: net/sched/sch_generic.c:488
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/xen-netfront.c:xennet_connect
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81a6c720-ffffffff81a6c766: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a54eb0)
Location: net/sched/sch_generic.c:513
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:xennet_connect
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81a54eb0-ffffffff81a54ef6: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0dbc0)
Location: net/sched/sch_generic.c:523
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:xennet_connect
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff81b0dbc0-ffffffff81b0dc06: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c94f90)
Location: net/sched/sch_generic.c:578
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_change_carrier
  - drivers/net/xen-netfront.c:xennet_connect
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down
```
**Symbols:**

```
ffffffff81c94f90-ffffffff81c94fe4: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e50a60)
Location: net/sched/sch_generic.c:575
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_change_carrier
  - drivers/net/xen-netfront.c:xennet_connect
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down
```
**Symbols:**

```
ffffffff81e50a60-ffffffff81e50ab4: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eac270)
Location: net/sched/sch_generic.c:575
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_change_carrier
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_open
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down
```
**Symbols:**

```
ffffffff81eac270-ffffffff81eac2c4: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f6ed00)
Location: net/sched/sch_generic.c:576
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_open
  - drivers/net/netkit.c:netkit_open
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_change_carrier
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_open
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down
```
**Symbols:**

```
ffffffff81f6ed00-ffffffff81f6ed5a: netif_carrier_on (STB_GLOBAL)
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
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c39898)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/mii.c:mii_check_link
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffff800010c39898-ffff800010c39958: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4bc1c)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/ethernet/ti/cpsw.c:cpsw_adjust_link
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
c0d4bc1c-c0d4bc90: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d326a0)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
c000000000d326a0-c000000000d32768: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007aac98)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffe0007aac98-ffffffe0007aacf2: netif_carrier_on (STB_GLOBAL)
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
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192df40)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff8192df40-ffffffff8192df84: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e7a40)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff818e7a40-ffffffff818e7a84: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197f0d0)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff8197f0d0-ffffffff8197f114: netif_carrier_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void netif_carrier_on(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a1630)
Location: net/sched/sch_generic.c:492
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_link_change
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_change_proto_down_generic
```
**Symbols:**

```
ffffffff819a1630-ffffffff819a1674: netif_carrier_on (STB_GLOBAL)
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
