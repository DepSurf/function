# Function: <code>dma_get_max_seg_size</code>

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
In arch/x86/kernel/amd_gart_64.c (ffffffff81066fb8)
Location: include/linux/dma-mapping.h:147
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff815adb4a)
Location: include/linux/dma-mapping.h:147
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81066d48)
Location: include/linux/dma-mapping.h:568
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81605a4b)
Location: include/linux/dma-mapping.h:568
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/spi/spi.c (ffffffff81645793)
Location: include/linux/dma-mapping.h:568
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a998)
Location: include/linux/dma-mapping.h:620
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81634f6b)
Location: include/linux/dma-mapping.h:620
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/spi/spi.c (ffffffff81676f34)
Location: include/linux/dma-mapping.h:620
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069cd8)
Location: include/linux/dma-mapping.h:651
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81649d67)
Location: include/linux/dma-mapping.h:651
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/spi/spi.c (ffffffff8168b640)
Location: include/linux/dma-mapping.h:651
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e588)
Location: include/linux/dma-mapping.h:659
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b2eb7)
Location: include/linux/dma-mapping.h:659
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/spi/spi.c (ffffffff816f4fd0)
Location: include/linux/dma-mapping.h:659
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810712b8)
Location: include/linux/dma-mapping.h:663
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ef103)
Location: include/linux/dma-mapping.h:663
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/spi/spi.c (ffffffff81732720)
Location: include/linux/dma-mapping.h:663
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810772b0)
Location: include/linux/dma-mapping.h:689
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81755110)
Location: include/linux/dma-mapping.h:689
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107acb0)
Location: include/linux/dma-mapping.h:714
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81791210)
Location: include/linux/dma-mapping.h:714
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107bda0)
Location: include/linux/dma-mapping.h:719
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817b4e00)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810834d5)
Location: include/linux/dma-mapping.h:805
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff8179227e)
Location: include/linux/dma-mapping.h:805
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8187b9f9)
Location: include/linux/dma-mapping.h:805
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81084cf7)
Location: include/linux/dma-mapping.h:452
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bea80)
Location: include/linux/dma-mapping.h:452
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8188abd9)
Location: include/linux/dma-mapping.h:452
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810858e7)
Location: include/linux/dma-mapping.h:494
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a23c3)
Location: include/linux/dma-mapping.h:494
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/spi/spi.c (ffffffff8186d569)
Location: include/linux/dma-mapping.h:494
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81094aa2)
Location: include/linux/dma-mapping.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182b4ac)
Location: include/linux/dma-mapping.h:474
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/spi/spi.c (ffffffff818fd549)
Location: include/linux/dma-mapping.h:474
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6d61)
Location: include/linux/dma-mapping.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-mapping.h:474
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/spi/spi.c (ffffffff81a4eb89)
Location: include/linux/dma-mapping.h:474
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810bffd1)
Location: include/linux/dma-mapping.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-mapping.h:479
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81bd03e9)
Location: include/linux/dma-mapping.h:479
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810c36b1)
Location: include/linux/dma-mapping.h:480
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-mapping.h:480
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81c28069)
Location: include/linux/dma-mapping.h:480
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810cbaf1)
Location: include/linux/dma-mapping.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-mapping.h:473
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81cda7b9)
Location: include/linux/dma-mapping.h:473
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
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
In drivers/iommu/dma-iommu.c (ffff8000108c9ca8)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/spi/spi.c (ffff8000109c84fc)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/mmc/host/mmci.c (ffff800010b44ae4)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_dmae_setup
  - drivers/mmc/host/mmci.c:mmci_dmae_setup
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
In arch/arm/mm/dma-mapping.c (c031d384)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:__iommu_map_sg
```
```
In drivers/spi/spi.c (c0ab20e8)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/mmc/host/mmci.c (c0c1e6b0)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_dmae_setup
  - drivers/mmc/host/mmci.c:mmci_dmae_setup
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2b370)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (c0cbaed0)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_pcm_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c0000000000522e0)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
```
```
In drivers/spi/spi.c (c000000000a89d14)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe00061899e)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107ada0)
Location: include/linux/dma-mapping.h:719
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817798e0)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a4d0)
Location: include/linux/dma-mapping.h:719
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81759690)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107ad50)
Location: include/linux/dma-mapping.h:719
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817a9c80)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107ce50)
Location: include/linux/dma-mapping.h:719
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817c3b10)
Location: include/linux/dma-mapping.h:719
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
</details>
</li>
</ul>

## Differences
