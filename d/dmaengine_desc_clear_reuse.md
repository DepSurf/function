# Function: <code>dmaengine_desc_clear_reuse</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff81707e9c)
Location: include/linux/dmaengine.h:1552
Inline: True
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
In drivers/dma/lgm/lgm-dma.c (ffffffff8178379c)
Location: include/linux/dmaengine.h:1550
Inline: True
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818ba3b8)
Location: include/linux/dmaengine.h:1573
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
In drivers/dma/hsu/hsu.c (ffffffff81a08434)
Location: include/linux/dmaengine.h:1553
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a08df8)
Location: include/linux/dmaengine.h:1553
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
In drivers/dma/hsu/hsu.c (ffffffff81a512a4)
Location: include/linux/dmaengine.h:1554
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a51c78)
Location: include/linux/dmaengine.h:1554
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
In drivers/dma/hsu/hsu.c (ffffffff81a9cff4)
Location: include/linux/dmaengine.h:1553
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d9c8)
Location: include/linux/dmaengine.h:1553
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
In drivers/dma/amba-pl08x.c (ffff8000108009c8)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804d88)
Location: include/linux/dmaengine.h:1383
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
In drivers/dma/amba-pl08x.c (c0922d7c)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/ti/edma.c (c092e0cc)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_free_chan_resources
```
```
In drivers/dma/ti/omap-dma.c (c0930d30)
Location: include/linux/dmaengine.h:1383
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
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
