# Function: <code>vchan_get_all_descriptors</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff817093fb)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81784dab)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb819)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
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
In drivers/dma/hsu/hsu.c (ffffffff81a082e9)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a4d9)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
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
In drivers/dma/hsu/hsu.c (ffffffff81a51159)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53359)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
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
In drivers/dma/hsu/hsu.c (ffffffff81a9cea9)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f109)
Location: drivers/dma/virt-dma.h:177
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
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
In drivers/dma/amba-pl08x.c (ffff800010801e60)
Location: drivers/dma/virt-dma.h:175
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/bcm2835-dma.c (ffff800010805054)
Location: drivers/dma/virt-dma.h:175
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
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
In drivers/dma/amba-pl08x.c (c0922558)
Location: drivers/dma/virt-dma.h:175
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/ti/edma.c (c092dff8)
Location: drivers/dma/virt-dma.h:175
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_terminate_all
```
```
In drivers/dma/ti/omap-dma.c (c0932790)
Location: drivers/dma/virt-dma.h:175
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
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
