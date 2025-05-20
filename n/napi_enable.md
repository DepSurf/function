# Function: <code>napi_enable</code>

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
In drivers/net/virtio_net.c (ffffffff815f1935)
Location: include/linux/netdevice.h:506
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff815fcb95)
Location: include/linux/netdevice.h:506
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/virtio_net.c (ffffffff81651245)
Location: include/linux/netdevice.h:510
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8165cad5)
Location: include/linux/netdevice.h:510
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8168aa04)
Location: include/linux/netdevice.h:500
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/xen-netfront.c (ffffffff8169fb9e)
Location: include/linux/netdevice.h:500
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/gro_cells.c (ffffffff817f9a9a)
Location: include/linux/netdevice.h:500
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
In drivers/net/tun.c (ffffffff817000c8)
Location: include/linux/netdevice.h:500
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff8170ad2c)
Location: include/linux/netdevice.h:500
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/gro_cells.c (ffffffff818773b1)
Location: include/linux/netdevice.h:500
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
In drivers/net/tun.c (ffffffff8173dcb2)
Location: include/linux/netdevice.h:502
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff81749598)
Location: include/linux/netdevice.h:502
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
```
```
In net/core/gro_cells.c (ffffffff818c8acd)
Location: include/linux/netdevice.h:502
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
In drivers/net/tun.c (ffffffff81761b38)
Location: include/linux/netdevice.h:513
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff8176d27d)
Location: include/linux/netdevice.h:513
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/gro_cells.c (ffffffff818f39ed)
Location: include/linux/netdevice.h:513
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
In drivers/net/tun.c (ffffffff8179f812)
Location: include/linux/netdevice.h:510
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817ab03a)
Location: include/linux/netdevice.h:510
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/gro_cells.c (ffffffff81952880)
Location: include/linux/netdevice.h:510
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
In drivers/net/tun.c (ffffffff817c3aaa)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817cea7a)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/gro_cells.c (ffffffff81988bd0)
Location: include/linux/netdevice.h:514
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
In drivers/net/tun.c (ffffffff8188f49c)
Location: include/linux/netdevice.h:519
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8189861b)
Location: include/linux/netdevice.h:519
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/gro_cells.c (ffffffff81a60827)
Location: include/linux/netdevice.h:519
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
In drivers/net/tun.c (ffffffff8189d81e)
Location: include/linux/netdevice.h:514
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff818a69f3)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/gro_cells.c (ffffffff81a690c7)
Location: include/linux/netdevice.h:514
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void napi_enable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e8d60)
Location: net/core/dev.c:6950
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_open
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff819e8d60-ffffffff819e8d9b: napi_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void napi_enable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a95410)
Location: net/core/dev.c:6936
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_open
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81a95410-ffffffff81a95457: napi_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void napi_enable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0bb40)
Location: net/core/dev.c:6431
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_open
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81c0bb40-ffffffff81c0bb93: napi_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void napi_enable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbbc40)
Location: net/core/dev.c:6418
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_open
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81dbbc40-ffffffff81dbbc8a: napi_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void napi_enable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2c3d0)
Location: net/core/dev.c:6399
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/xen-netfront.c:xennet_open
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81e2c3d0-ffffffff81e2c439: napi_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void napi_enable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eea430)
Location: net/core/dev.c:6515
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/xen-netfront.c:xennet_open
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81eea430-ffffffff81eea499: napi_enable (STB_GLOBAL)
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
In drivers/net/tun.c (ffff8000109de64c)
Location: include/linux/netdevice.h:514
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e4170)
Location: include/linux/netdevice.h:514
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea83c)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/xen-netfront.c (ffff800010a07c28)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/gro_cells.c (ffff800010c30d6c)
Location: include/linux/netdevice.h:514
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void napi_enable(struct napi_struct *n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac35a8)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accc5c)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad68cc)
Location: include/linux/netdevice.h:514
Inline: True
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
```
```
In net/core/gro_cells.c (c0d47bf0)
Location: include/linux/netdevice.h:514
Inline: True
```
**Symbols:**

```
c0ad68cc-c0ad6910: napi_enable (STB_LOCAL)
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
In drivers/net/tun.c (c000000000a9f7c4)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/gro_cells.c (c000000000d29c4c)
Location: include/linux/netdevice.h:514
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
In drivers/net/tun.c (ffffffe000628ec6)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/gro_cells.c (ffffffe0007a6c84)
Location: include/linux/netdevice.h:514
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
In drivers/net/tun.c (ffffffff8178858a)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff8179369a)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/gro_cells.c (ffffffff81928a40)
Location: include/linux/netdevice.h:514
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
In drivers/net/tun.c (ffffffff81767eda)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In net/core/gro_cells.c (ffffffff818e27f0)
Location: include/linux/netdevice.h:514
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
In drivers/net/tun.c (ffffffff817b892a)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817c38fa)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/gro_cells.c (ffffffff81979bd0)
Location: include/linux/netdevice.h:514
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
In drivers/net/tun.c (ffffffff817d186a)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/xen-netfront.c (ffffffff817ddbba)
Location: include/linux/netdevice.h:514
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
```
In net/core/gro_cells.c (ffffffff8199c100)
Location: include/linux/netdevice.h:514
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
