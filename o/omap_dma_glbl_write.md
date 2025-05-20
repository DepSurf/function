# Function: <code>omap_dma_glbl_write</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
void omap_dma_glbl_write(struct omap_dmadev *od, unsigned int reg, unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/ti/omap-dma.c (c0930ad8)
Location: drivers/dma/ti/omap-dma.c:329
Inline: False
Direct callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_remove
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_alloc_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_alloc_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_alloc_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_irq
  - drivers/dma/ti/omap-dma.c:omap_dma_stop
  - drivers/dma/ti/omap-dma.c:omap_dma_stop
```
**Symbols:**

```
c0930ad8-c0930b44: omap_dma_glbl_write (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
