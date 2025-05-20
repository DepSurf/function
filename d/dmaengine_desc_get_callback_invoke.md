# Function: <code>dmaengine_desc_get_callback_invoke</code>

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
In drivers/dma/mv_xor.c (ffff8000108068dc)
Location: drivers/dma/dmaengine.h:152
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/mv_xor_v2.c (ffff80001080853c)
Location: drivers/dma/dmaengine.h:152
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
```
```
In drivers/dma/mxs-dma.c (ffff800010809cfc)
Location: drivers/dma/dmaengine.h:152
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_tasklet
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
In drivers/dma/mv_xor.c (c09245e8)
Location: drivers/dma/dmaengine.h:152
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/mxs-dma.c (c0926c60)
Location: drivers/dma/dmaengine.h:152
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_tasklet
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
