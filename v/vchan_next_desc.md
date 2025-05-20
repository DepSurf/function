# Function: <code>vchan_next_desc</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff8170811e)
Location: drivers/dma/virt-dma.h:161
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81783a36)
Location: drivers/dma/virt-dma.h:161
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818ba69d)
Location: drivers/dma/virt-dma.h:161
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
In drivers/dma/hsu/hsu.c (ffffffff81a0854b)
Location: drivers/dma/virt-dma.h:161
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0910d)
Location: drivers/dma/virt-dma.h:161
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
In drivers/dma/hsu/hsu.c (ffffffff81a513bb)
Location: drivers/dma/virt-dma.h:161
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a51f8d)
Location: drivers/dma/virt-dma.h:161
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
In drivers/dma/hsu/hsu.c (ffffffff81a9d10b)
Location: drivers/dma/virt-dma.h:161
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9dcdd)
Location: drivers/dma/virt-dma.h:161
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
In drivers/dma/amba-pl08x.c (ffff8000108021a0)
Location: drivers/dma/virt-dma.h:159
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
```
```
In drivers/dma/bcm2835-dma.c (ffff800010803cf8)
Location: drivers/dma/virt-dma.h:159
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_start_desc
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
In drivers/dma/amba-pl08x.c (c0922994)
Location: drivers/dma/virt-dma.h:159
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
```
```
In drivers/dma/ti/edma.c (c092d95c)
Location: drivers/dma/virt-dma.h:159
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_execute
```
```
In drivers/dma/ti/omap-dma.c (c0930e24)
Location: drivers/dma/virt-dma.h:159
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_start_desc
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
