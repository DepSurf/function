# Function: <code>vchan_tx_prep</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff8170884c)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
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
In drivers/dma/lgm/lgm-dma.c (ffffffff8178466c)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb32f)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
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
In drivers/dma/hsu/hsu.c (ffffffff81a07e5c)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a09def)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
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
In drivers/dma/hsu/hsu.c (ffffffff81a50ccc)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a52c7f)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
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
In drivers/dma/hsu/hsu.c (ffffffff81a9ca21)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9e9fe)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
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
In drivers/dma/amba-pl08x.c (ffff8000108024cc)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804464)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_cyclic
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_memcpy
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
In drivers/dma/amba-pl08x.c (c09235cc)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy
```
```
In drivers/dma/ti/edma.c (c09303f8)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_prep_dma_cyclic
  - drivers/dma/ti/edma.c:edma_prep_dma_memcpy
  - drivers/dma/ti/edma.c:edma_prep_slave_sg
```
```
In drivers/dma/ti/omap-dma.c (c093265c)
Location: drivers/dma/virt-dma.h:56
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_dma_memcpy
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_dma_cyclic
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg
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
