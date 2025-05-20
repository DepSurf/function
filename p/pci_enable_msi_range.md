# Function: <code>pci_enable_msi_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81454790)
Location: drivers/pci/msi.c:1045
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81454790-ffffffff81454a16: pci_enable_msi_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1580)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff814a1580-ffffffff814a1592: pci_enable_msi_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c3100)
Location: drivers/pci/msi.c:1124
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff814c3100-ffffffff814c3112: pci_enable_msi_range (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
