# Function: <code>page_to_phys</code>

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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4c9c)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/events/core.c (c000000000350bb0)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/percpu.c (c0000000003a44e8)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In block/bio.c (c00000000076b068)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_try_merge_page
```
```
In block/blk-merge.c (c000000000780428)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (c0000000007bd4f0)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In lib/kfifo.c (c0000000007d9864)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
```
```
In drivers/virtio/virtio_ring.c (c0000000008cb7c0)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
```
```
In drivers/char/agp/backend.c (c000000000952250)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_add_bridge
```
```
In drivers/char/agp/generic.c (c000000000956cd0)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_insert_memory
```
```
In drivers/iommu/iommu.c (c00000000096b8d0)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b598)
Location: arch/powerpc/include/asm/io.h:800
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
</details>
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
