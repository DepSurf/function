# Function: <code>to_virt_chan</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81706fc7)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_dma_desc_free_list
  - drivers/dma/virt-dma.c:vchan_complete
  - drivers/dma/virt-dma.c:vchan_tx_desc_free
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81708b1e)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
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
In drivers/dma/virt-dma.c (ffffffff81782877)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_dma_desc_free_list
  - drivers/dma/virt-dma.c:vchan_complete
  - drivers/dma/virt-dma.c:vchan_tx_desc_free
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81784936)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
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
In drivers/dma/virt-dma.c (0)
Location: drivers/dma/virt-dma.h:39
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/virt-dma.h:39
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
In drivers/dma/virt-dma.c (0)
Location: drivers/dma/virt-dma.h:39
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: drivers/dma/virt-dma.h:39
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/virt-dma.h:39
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
In drivers/dma/virt-dma.c (0)
Location: drivers/dma/virt-dma.h:39
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: drivers/dma/virt-dma.h:39
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/virt-dma.h:39
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
In drivers/dma/virt-dma.c (0)
Location: drivers/dma/virt-dma.h:39
Inline: True
```
```
In drivers/dma/hsu/hsu.c (0)
Location: drivers/dma/virt-dma.h:39
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/virt-dma.h:39
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
In drivers/dma/virt-dma.c (ffff8000107fe830)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
  - drivers/dma/virt-dma.c:vchan_tx_desc_free
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/amba-pl08x.c (ffff800010802154)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804bcc)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
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
In drivers/dma/virt-dma.c (c091fb40)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
  - drivers/dma/virt-dma.c:vchan_tx_desc_free
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/amba-pl08x.c (c0922954)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/ti/edma.c (c092f84c)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:edma_synchronize
  - drivers/dma/ti/edma.c:edma_terminate_all
  - drivers/dma/ti/edma.c:edma_terminate_all
```
```
In drivers/dma/ti/omap-dma.c (c0930608)
Location: drivers/dma/virt-dma.h:39
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_synchronize
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_callback
  - drivers/dma/ti/omap-dma.c:omap_dma_callback
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
