# Function: <code>set_iommu_table_base</code>

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
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d55fc)
Location: arch/powerpc/include/asm/iommu.h:136
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda2_take_ownership
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_dma
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_dma_dev_setup
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f0c74)
Location: arch/powerpc/include/asm/iommu.h:136
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeries
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeries
```
```
In arch/powerpc/platforms/pseries/vio.c (c0000000001018f0)
Location: arch/powerpc/include/asm/iommu.h:136
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
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
