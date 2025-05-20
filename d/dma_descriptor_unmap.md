# Function: <code>dma_descriptor_unmap</code>

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
In drivers/dma/amba-pl08x.c (ffff800010800570)
Location: include/linux/dmaengine.h:540
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_desc_free
```
```
In drivers/dma/mv_xor.c (ffff8000108068cc)
Location: include/linux/dmaengine.h:540
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/mv_xor_v2.c (ffff80001080852c)
Location: include/linux/dmaengine.h:540
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
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
In drivers/dma/amba-pl08x.c (c0920d18)
Location: include/linux/dmaengine.h:540
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_desc_free
```
```
In drivers/dma/mv_xor.c (c09245d0)
Location: include/linux/dmaengine.h:540
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
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
