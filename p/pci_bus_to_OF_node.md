# Function: <code>pci_bus_to_OF_node</code>

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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffff8000106f9a80)
Location: include/linux/pci.h:2307
Inline: True
Inline callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c08920f0)
Location: include/linux/pci.h:2307
Inline: True
Inline callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
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
In arch/powerpc/kernel/eeh_pe.c (c000000000047eec)
Location: include/linux/pci.h:2307
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_loc_get
```
```
In arch/powerpc/kernel/pci_dn.c (c00000000006acb0)
Location: include/linux/pci.h:2307
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_dn.c:remove_dev_pci_data
  - arch/powerpc/kernel/pci_dn.c:add_dev_pci_data
  - arch/powerpc/kernel/pci_dn.c:pci_get_pdn_by_devfn
```
```
In arch/powerpc/kernel/pci-hotplug.c (c00000000006b2e4)
Location: include/linux/pci.h:2307
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices
  - arch/powerpc/kernel/pci-hotplug.c:find_bus_among_children
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f0ef4)
Location: include/linux/pci.h:2307
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_bus_setup_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_bus_setup_pSeries
```
```
In drivers/pci/of.c (c000000000877330)
Location: include/linux/pci.h:2307
Inline: True
Inline callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
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
In drivers/pci/of.c (ffffffe0004c9d7a)
Location: include/linux/pci.h:2307
Inline: True
Inline callers:
  - drivers/pci/of.c:of_irq_parse_and_map_pci
```
</details>
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
