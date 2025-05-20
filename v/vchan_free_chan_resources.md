# Function: <code>vchan_free_chan_resources</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff81707d20)
Location: drivers/dma/virt-dma.h:187
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81783620)
Location: drivers/dma/virt-dma.h:187
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818ba25a)
Location: drivers/dma/virt-dma.h:187
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
In drivers/dma/hsu/hsu.c (ffffffff81a082d2)
Location: drivers/dma/virt-dma.h:187
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a08c9a)
Location: drivers/dma/virt-dma.h:187
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
In drivers/dma/hsu/hsu.c (ffffffff81a51142)
Location: drivers/dma/virt-dma.h:187
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a51b1a)
Location: drivers/dma/virt-dma.h:187
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
In drivers/dma/hsu/hsu.c (ffffffff81a9ce92)
Location: drivers/dma/virt-dma.h:187
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d86a)
Location: drivers/dma/virt-dma.h:187
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
In drivers/dma/amba-pl08x.c (ffff8000108008c0)
Location: drivers/dma/virt-dma.h:184
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804c80)
Location: drivers/dma/virt-dma.h:184
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
In drivers/dma/amba-pl08x.c (c0922c88)
Location: drivers/dma/virt-dma.h:184
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/ti/edma.c (c092dfd8)
Location: drivers/dma/virt-dma.h:184
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_free_chan_resources
```
```
In drivers/dma/ti/omap-dma.c (c0930c40)
Location: drivers/dma/virt-dma.h:184
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
