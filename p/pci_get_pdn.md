# Function: <code>pci_get_pdn</code>

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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pci_dn *pci_get_pdn(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci_dn.c (c00000000006a850)
Location: arch/powerpc/kernel/pci_dn.c:95
Inline: True
Direct callers:
  - arch/powerpc/kernel/eeh_pe.c:eeh_add_to_parent_pe
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_notify_resume_store
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_notify_resume_show
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_notify_resume_show
  - arch/powerpc/kernel/pci_dn.c:remove_dev_pci_data
  - arch/powerpc/kernel/pci_dn.c:remove_dev_pci_data
  - arch/powerpc/kernel/pci_dn.c:add_dev_pci_data
  - arch/powerpc/kernel/pci_dn.c:add_dev_pci_data
  - arch/powerpc/kernel/pci-hotplug.c:pcibios_release_device
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_release_device
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_iov_resource_alignment
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup_iov_resources
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_dma_dev_setup
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_release_m64
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_same_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_dev_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_resource_shift
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_configure_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_deconfigure_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_get_pe
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_pci_fixup_vf_mps
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_pcibios_bus_add_device
  - arch/powerpc/platforms/pseries/pci.c:pseries_pcibios_sriov_disable
  - arch/powerpc/platforms/pseries/pci.c:pseries_associate_pes
  - arch/powerpc/platforms/pseries/pci.c:pseries_set_pe_num
  - arch/powerpc/platforms/pseries/pci.c:pseries_send_map_pe
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_notify_resume
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_notify_resume
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_pcibios_bus_add_device
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_pcibios_bus_add_device
```
**Symbols:**

```
c00000000006a850-c00000000006a950: pci_get_pdn (STB_GLOBAL)
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
