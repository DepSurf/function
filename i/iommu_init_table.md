# Function: <code>iommu_init_table</code>

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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct iommu_table *iommu_init_table(struct iommu_table *tbl, int nid, long unsigned int res_start, long unsigned int res_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c000000000052870)
Location: arch/powerpc/kernel/iommu.c:682
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeries
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_bus_setup_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_bus_setup_pSeries
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
```
**Symbols:**

```
c000000000052870-c000000000052c04: iommu_init_table (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
