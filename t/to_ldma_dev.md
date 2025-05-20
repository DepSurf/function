# Function: <code>to_ldma_dev</code>

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
In drivers/dma/lgm/lgm-dma.c (ffffffff81707abf)
Location: drivers/dma/lgm/lgm-dma.c:295
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:ldma_tx_status
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_desc_hw_cfg
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
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
In drivers/dma/lgm/lgm-dma.c (ffffffff8178338f)
Location: drivers/dma/lgm/lgm-dma.c:295
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:ldma_tx_status
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_desc_hw_cfg
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
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
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:295
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:295
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:295
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: drivers/dma/lgm/lgm-dma.c:295
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
