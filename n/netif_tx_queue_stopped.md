# Function: <code>netif_tx_queue_stopped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815faabf)
Location: include/linux/netdevice.h:2696
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8165a9a1)
Location: include/linux/netdevice.h:2919
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff81688701)
Location: include/linux/netdevice.h:2858
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169dea5)
Location: include/linux/netdevice.h:2885
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81709048)
Location: include/linux/netdevice.h:2910
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81747b93)
Location: include/linux/netdevice.h:3019
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
In drivers/net/xen-netfront.c (ffffffff8176bc7c)
Location: include/linux/netdevice.h:3113
Inline: True
```
```
In net/core/dev.c (ffffffff818b465c)
Location: include/linux/netdevice.h:3113
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff817a9a6c)
Location: include/linux/netdevice.h:3130
Inline: True
```
```
In net/core/dev.c (ffffffff81900f82)
Location: include/linux/netdevice.h:3130
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff817cd4dc)
Location: include/linux/netdevice.h:3144
Inline: True
```
```
In net/core/dev.c (ffffffff819332b2)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff81897f7e)
Location: include/linux/netdevice.h:3257
Inline: True
```
```
In net/core/dev.c (ffffffff81a08122)
Location: include/linux/netdevice.h:3257
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff818a633e)
Location: include/linux/netdevice.h:3411
Inline: True
```
```
In net/core/dev.c (ffffffff81a09798)
Location: include/linux/netdevice.h:3411
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff81889712)
Location: include/linux/netdevice.h:3478
Inline: True
```
```
In net/core/dev.c (ffffffff819f010a)
Location: include/linux/netdevice.h:3478
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff8191bad5)
Location: include/linux/netdevice.h:3490
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81aa153a)
Location: include/linux/netdevice.h:3490
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff81a70c14)
Location: include/linux/netdevice.h:3281
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81c19466)
Location: include/linux/netdevice.h:3281
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff81c064dd)
Location: include/linux/netdevice.h:3306
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81dca476)
Location: include/linux/netdevice.h:3306
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff81c6bbdb)
Location: include/linux/netdevice.h:3370
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81e3aff6)
Location: include/linux/netdevice.h:3370
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff81d2059d)
Location: include/linux/netdevice.h:3449
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
```
In net/core/dev.c (ffffffff81ef9363)
Location: include/linux/netdevice.h:3449
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e34d0)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e7368)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
```
```
In drivers/net/xen-netfront.c (ffff800010a06d04)
Location: include/linux/netdevice.h:3144
Inline: True
```
```
In net/core/dev.c (ffff800010bd1324)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/ethernet/freescale/fec_main.c (c0acc154)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad19c0)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_handler
```
```
In net/core/dev.c (c0cebf88)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caf5d8)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b894)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff817920fc)
Location: include/linux/netdevice.h:3144
Inline: True
```
```
In net/core/dev.c (ffffffff818d32b2)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188d142)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff817c235c)
Location: include/linux/netdevice.h:3144
Inline: True
```
```
In net/core/dev.c (ffffffff819242b2)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/xen-netfront.c (ffffffff817dc61c)
Location: include/linux/netdevice.h:3144
Inline: True
```
```
In net/core/dev.c (ffffffff81945712)
Location: include/linux/netdevice.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
</details>
</li>
</ul>

## Differences
