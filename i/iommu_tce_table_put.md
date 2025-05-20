# Function: <code>iommu_tce_table_put</code>

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
int iommu_tce_table_put(struct iommu_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c000000000051d40)
Location: arch/powerpc/kernel/iommu.c:780
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda2_take_ownership
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda2_take_ownership
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu_peers_unset_window
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_unlink_table_and_group
  - arch/powerpc/platforms/pseries/vio.c:vio_dev_release
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_free_table
```
**Symbols:**

```
c000000000051d40-c000000000051eb0: iommu_tce_table_put (STB_GLOBAL)
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
