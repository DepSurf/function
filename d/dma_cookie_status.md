# Function: <code>dma_cookie_status</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff817085d0)
Location: drivers/dma/dmaengine.h:68
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
In drivers/dma/lgm/lgm-dma.c (ffffffff817843f0)
Location: drivers/dma/dmaengine.h:68
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb09f)
Location: drivers/dma/dmaengine.h:68
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
In drivers/dma/hsu/hsu.c (ffffffff81a07f15)
Location: drivers/dma/dmaengine.h:68
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a09b4f)
Location: drivers/dma/dmaengine.h:68
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
In drivers/dma/hsu/hsu.c (ffffffff81a50d85)
Location: drivers/dma/dmaengine.h:68
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a529df)
Location: drivers/dma/dmaengine.h:68
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
In drivers/dma/hsu/hsu.c (ffffffff81a9cad5)
Location: drivers/dma/dmaengine.h:68
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9e72f)
Location: drivers/dma/dmaengine.h:68
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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
enum dma_status dma_cookie_status(struct dma_chan *chan, dma_cookie_t cookie, struct dma_tx_state *state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/amba-pl08x.c (ffff8000108036e8)
Location: drivers/dma/dmaengine.h:68
Inline: True
```
```
In drivers/dma/bcm2835-dma.c (ffff8000108058b0)
Location: drivers/dma/dmaengine.h:68
Inline: True
```
```
In drivers/dma/mv_xor.c (ffff800010806c8c)
Location: drivers/dma/dmaengine.h:68
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_status
```
```
In drivers/dma/mv_xor_v2.c (ffff8000108082f0)
Location: drivers/dma/dmaengine.h:68
Inline: False
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080adc8)
Location: drivers/dma/dmaengine.h:68
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_status
```
**Symbols:**

```
ffff8000108082f0-ffff800010808338: dma_cookie_status (STB_LOCAL)
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
In drivers/dma/amba-pl08x.c (c0921058)
Location: drivers/dma/dmaengine.h:68
Inline: True
```
```
In drivers/dma/mv_xor.c (c0924944)
Location: drivers/dma/dmaengine.h:68
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_status
```
```
In drivers/dma/ipu/ipu_idmac.c (c092744c)
Location: drivers/dma/dmaengine.h:68
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_status
```
```
In drivers/dma/tegra20-apb-dma.c (c092b0c4)
Location: drivers/dma/dmaengine.h:68
Inline: True
```
```
In drivers/dma/ti/edma.c (c092e5fc)
Location: drivers/dma/dmaengine.h:68
Inline: True
```
```
In drivers/dma/ti/omap-dma.c (c093206c)
Location: drivers/dma/dmaengine.h:68
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
<b>Arch</b>
<ul>
</ul>
