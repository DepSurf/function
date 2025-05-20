# Function: <code>async_tx_ack</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/mx3fb.c (ffff80001075f4e8)
Location: include/linux/dmaengine.h:1187
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
```
```
In drivers/dma/mv_xor.c (ffff800010807d5c)
Location: include/linux/dmaengine.h:1187
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
```
```
In drivers/dma/mv_xor_v2.c (ffff8000108091e8)
Location: include/linux/dmaengine.h:1187
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff800010809fcc)
Location: include/linux/dmaengine.h:1187
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
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
In drivers/video/fbdev/mx3fb.c (c08e2588)
Location: include/linux/dmaengine.h:1187
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
```
```
In drivers/dma/mv_xor.c (c0925b28)
Location: include/linux/dmaengine.h:1187
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
```
```
In drivers/dma/mxs-dma.c (c0926db8)
Location: include/linux/dmaengine.h:1187
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
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
