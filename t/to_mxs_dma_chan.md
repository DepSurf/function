# Function: <code>to_mxs_dma_chan</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/mxs-dma.c (ffff8000108099c4)
Location: drivers/dma/mxs-dma.c:198
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_filter_fn
  - drivers/dma/mxs-dma.c:mxs_dma_tx_status
  - drivers/dma/mxs-dma.c:mxs_dma_terminate_all
  - drivers/dma/mxs-dma.c:mxs_dma_prep_dma_cyclic
  - drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_resume_chan
  - drivers/dma/mxs-dma.c:mxs_dma_pause_chan
  - drivers/dma/mxs-dma.c:mxs_dma_enable_chan
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/mxs-dma.c (c0926434)
Location: drivers/dma/mxs-dma.c:198
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_filter_fn
  - drivers/dma/mxs-dma.c:mxs_dma_tx_status
  - drivers/dma/mxs-dma.c:mxs_dma_terminate_all
  - drivers/dma/mxs-dma.c:mxs_dma_prep_dma_cyclic
  - drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_resume_chan
  - drivers/dma/mxs-dma.c:mxs_dma_pause_chan
  - drivers/dma/mxs-dma.c:mxs_dma_enable_chan
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
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
