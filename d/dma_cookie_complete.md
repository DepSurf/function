# Function: <code>dma_cookie_complete</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81708a36)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:dma_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81784856)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:dma_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb51e)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:dma_work
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
In drivers/dma/hsu/hsu.c (ffffffff81a0783b)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a03e)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:dma_work
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
In drivers/dma/hsu/hsu.c (ffffffff81a506cb)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a52eb6)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:dma_work
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
In drivers/dma/hsu/hsu.c (ffffffff81a9c39b)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9ec66)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:dma_work
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
In drivers/dma/amba-pl08x.c (ffff800010802154)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
```
```
In drivers/dma/bcm2835-dma.c (ffff800010805340)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808520)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
```
```
In drivers/dma/mxs-dma.c (ffff80001080a19c)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080c828)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
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
In drivers/dma/amba-pl08x.c (c0922954)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
```
```
In drivers/dma/mxs-dma.c (c0926b34)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
```
```
In drivers/dma/ipu/ipu_idmac.c (c0929018)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
```
```
In drivers/dma/tegra20-apb-dma.c (c092ab50)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:handle_once_dma_done
```
```
In drivers/dma/ti/edma.c (c092f888)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
```
```
In drivers/dma/ti/omap-dma.c (c09323c4)
Location: drivers/dma/dmaengine.h:52
Inline: True
Inline callers:
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
