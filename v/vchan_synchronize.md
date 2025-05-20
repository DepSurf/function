# Function: <code>vchan_synchronize</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff817092eb)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81784c9b)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb6fb)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
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
In drivers/dma/hsu/hsu.c (ffffffff81a07963)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a3ab)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
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
In drivers/dma/hsu/hsu.c (ffffffff81a507f3)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a5322b)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
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
In drivers/dma/hsu/hsu.c (ffffffff81a9c4c3)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9efdb)
Location: drivers/dma/virt-dma.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
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
In drivers/dma/amba-pl08x.c (ffff800010800a70)
Location: drivers/dma/virt-dma.h:208
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804b80)
Location: drivers/dma/virt-dma.h:208
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize
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
In drivers/dma/amba-pl08x.c (c09205fc)
Location: drivers/dma/virt-dma.h:208
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
```
```
In drivers/dma/ti/edma.c (c092cbbc)
Location: drivers/dma/virt-dma.h:208
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_synchronize
```
```
In drivers/dma/ti/omap-dma.c (c09305d8)
Location: drivers/dma/virt-dma.h:208
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_synchronize
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
