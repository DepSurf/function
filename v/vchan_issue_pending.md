# Function: <code>vchan_issue_pending</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff817080c6)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
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
In drivers/dma/lgm/lgm-dma.c (ffffffff817839de)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818ba64d)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
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
In drivers/dma/hsu/hsu.c (ffffffff81a084d3)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a090bd)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
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
In drivers/dma/hsu/hsu.c (ffffffff81a51343)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a51f3d)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
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
In drivers/dma/hsu/hsu.c (ffffffff81a9d093)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9dc8d)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
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
In drivers/dma/amba-pl08x.c (ffff800010803478)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804eac)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_issue_pending
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
In drivers/dma/amba-pl08x.c (c0922708)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
```
```
In drivers/dma/ti/edma.c (c092da74)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_issue_pending
```
```
In drivers/dma/ti/omap-dma.c (c0930f9c)
Location: drivers/dma/virt-dma.h:82
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_issue_pending
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
