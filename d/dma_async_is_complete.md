# Function: <code>dma_async_is_complete</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff817085e3)
Location: include/linux/dmaengine.h:1455
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_tx_status
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81784403)
Location: include/linux/dmaengine.h:1453
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_tx_status
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb0b2)
Location: include/linux/dmaengine.h:1476
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_tx_status
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
In drivers/dma/hsu/hsu.c (ffffffff81a07f2c)
Location: include/linux/dmaengine.h:1456
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a09b62)
Location: include/linux/dmaengine.h:1456
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_tx_status
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
In drivers/dma/hsu/hsu.c (ffffffff81a50d9c)
Location: include/linux/dmaengine.h:1457
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a529f2)
Location: include/linux/dmaengine.h:1457
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_tx_status
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
In drivers/dma/hsu/hsu.c (ffffffff81a9caec)
Location: include/linux/dmaengine.h:1456
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9e742)
Location: include/linux/dmaengine.h:1456
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_tx_status
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
In drivers/dma/amba-pl08x.c (ffff8000108036f4)
Location: include/linux/dmaengine.h:1278
Inline: True
```
```
In drivers/dma/bcm2835-dma.c (ffff8000108058bc)
Location: include/linux/dmaengine.h:1278
Inline: True
```
```
In drivers/dma/mv_xor.c (ffff800010806c98)
Location: include/linux/dmaengine.h:1278
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_status
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808300)
Location: include/linux/dmaengine.h:1278
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:dma_cookie_status
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080add4)
Location: include/linux/dmaengine.h:1278
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_status
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
In drivers/dma/amba-pl08x.c (c0921074)
Location: include/linux/dmaengine.h:1278
Inline: True
```
```
In drivers/dma/mv_xor.c (c0924960)
Location: include/linux/dmaengine.h:1278
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_status
```
```
In drivers/dma/ipu/ipu_idmac.c (c0927460)
Location: include/linux/dmaengine.h:1278
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_status
```
```
In drivers/dma/tegra20-apb-dma.c (c092b0e0)
Location: include/linux/dmaengine.h:1278
Inline: True
```
```
In drivers/dma/ti/edma.c (c092e618)
Location: include/linux/dmaengine.h:1278
Inline: True
```
```
In drivers/dma/ti/omap-dma.c (c093208c)
Location: include/linux/dmaengine.h:1278
Inline: True
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
