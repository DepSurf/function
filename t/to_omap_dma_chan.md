# Function: <code>to_omap_dma_chan</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/ti/omap-dma.c (c093057c)
Location: drivers/dma/ti/omap-dma.c:216
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_filter_fn
  - drivers/dma/ti/omap-dma.c:omap_dma_resume
  - drivers/dma/ti/omap-dma.c:omap_dma_pause
  - drivers/dma/ti/omap-dma.c:omap_dma_synchronize
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_slave_config
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_dma_memcpy
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_dma_cyclic
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg
  - drivers/dma/ti/omap-dma.c:omap_dma_issue_pending
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_alloc_chan_resources
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
