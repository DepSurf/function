# Function: <code>__dma_cap_zero</code>

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
In drivers/rapidio/rio.c (ffffffff814596ef)
Location: include/linux/dmaengine.h:1052
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff814bd713)
Location: include/linux/dmaengine.h:1052
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509510)
Location: include/linux/dmaengine.h:1052
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff814a717f)
Location: include/linux/dmaengine.h:1196
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff8150d509)
Location: include/linux/dmaengine.h:1196
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b420)
Location: include/linux/dmaengine.h:1196
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff814c928f)
Location: include/linux/dmaengine.h:1220
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81539639)
Location: include/linux/dmaengine.h:1220
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81587c0a)
Location: include/linux/dmaengine.h:1220
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff814d50ef)
Location: include/linux/dmaengine.h:1231
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff8154ce92)
Location: include/linux/dmaengine.h:1231
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c09a)
Location: include/linux/dmaengine.h:1231
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8151559f)
Location: include/linux/dmaengine.h:1220
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff815b0408)
Location: include/linux/dmaengine.h:1220
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8160139a)
Location: include/linux/dmaengine.h:1220
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8154a94f)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff815e8864)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163a65a)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1227
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1227
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1227
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1215
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1215
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1215
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1347
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1347
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1347
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1392
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1392
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1392
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1394
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1394
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8170974f)
Location: include/linux/dmaengine.h:1394
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1394
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1392
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1392
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81785105)
Location: include/linux/dmaengine.h:1392
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1392
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
In drivers/rapidio/rio.c (ffffffff817fe58f)
Location: include/linux/dmaengine.h:1415
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/dma/dmaengine.c (ffffffff818b8755)
Location: include/linux/dmaengine.h:1415
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbce5)
Location: include/linux/dmaengine.h:1415
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff819256da)
Location: include/linux/dmaengine.h:1415
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8192bdea)
Location: include/linux/dmaengine.h:1395
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81a05c55)
Location: include/linux/dmaengine.h:1395
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a8d9)
Location: include/linux/dmaengine.h:1395
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a8210a)
Location: include/linux/dmaengine.h:1395
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff8197005a)
Location: include/linux/dmaengine.h:1396
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81a4eb15)
Location: include/linux/dmaengine.h:1396
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53760)
Location: include/linux/dmaengine.h:1396
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acd70a)
Location: include/linux/dmaengine.h:1396
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (ffffffff819ba06a)
Location: include/linux/dmaengine.h:1395
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/dma/dmaengine.c (ffffffff81a9a7b5)
Location: include/linux/dmaengine.h:1395
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f510)
Location: include/linux/dmaengine.h:1395
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b207da)
Location: include/linux/dmaengine.h:1395
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/mv_xor_v2.c (ffff800010809214)
Location: include/linux/dmaengine.h:1217
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/linux/dmaengine.h:1217
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/ti/edma.c (c092ef60)
Location: include/linux/dmaengine.h:1217
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In sound/core/pcm_dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
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
In drivers/rapidio/rio.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dmaengine.h:1217
Inline: True
```
</details>
</li>
</ul>

## Differences
