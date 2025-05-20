# Function: <code>dma_unmap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff814be0d6)
Location: include/asm-generic/dma-mapping-common.h:92
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815223af)
Location: include/asm-generic/dma-mapping-common.h:92
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_cleanup
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/dma-mapping-common.h:92
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8150dd66)
Location: include/linux/dma-mapping.h:250
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150faf8)
Location: include/linux/dma-mapping.h:250
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81575206)
Location: include/linux/dma-mapping.h:250
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/dma-mapping.h:250
Inline: True
```
</details>
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
