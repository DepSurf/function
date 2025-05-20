# Function: <code>pe_level_printk</code>

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
void pe_level_printk(const struct pnv_ioda_pe *pe, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d5060)
Location: arch/powerpc/platforms/powernv/pci-ioda.c:55
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_free_pe_seg
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_unset_window
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_unset_window
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_set_bypass
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_set_bypass
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_set_bypass
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_set_window
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_set_window
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_dev_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_configure_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_configure_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_configure_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_deconfigure_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_deconfigure_pe
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu_take_ownership
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu_unset_window
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu_unset_window
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu_set_window
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu_set_window
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_cxl_ioda_msi_setup
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_phb_to_cxl_mode
```
**Symbols:**

```
c0000000000d5060-c0000000000d5228: pe_level_printk (STB_GLOBAL)
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
