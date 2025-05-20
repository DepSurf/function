# Function: <code>pci_dev_to_eeh_dev</code>

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
In arch/powerpc/kernel/eeh.c (c00000000004432c)
Location: include/linux/pci.h:2325
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:eeh_dev_check_write
  - arch/powerpc/kernel/eeh.c:eeh_iommu_group_to_pe
  - arch/powerpc/kernel/eeh.c:eeh_dev_release
  - arch/powerpc/kernel/eeh.c:eeh_dev_open
  - arch/powerpc/kernel/eeh.c:eeh_remove_device
  - arch/powerpc/kernel/eeh.c:pcibios_set_pcie_reset_state
```
```
In arch/powerpc/kernel/eeh_cache.c (c0000000000484a0)
Location: include/linux/pci.h:2325
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_insert_dev
```
```
In arch/powerpc/kernel/eeh_sysfs.c (c00000000004b9a8)
Location: include/linux/pci.h:2325
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_notify_resume_store
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_notify_resume_show
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_pe_state_store
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_pe_state_show
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_show_eeh_pe_config_addr
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_show_eeh_mode
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d23b0)
Location: include/linux/pci.h:2325
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_npu_disable_device
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
