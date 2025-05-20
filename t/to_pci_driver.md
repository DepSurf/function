# Function: <code>to_pci_driver</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810213fa)
Location: include/linux/pci.h:928
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/probe_roms.c (ffffffff810496f5)
Location: include/linux/pci.h:928
Inline: True
```
```
In drivers/pci/pci-driver.c (ffffffff817c8110)
Location: include/linux/pci.h:928
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_cleanup
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_bus_match
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
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
In arch/x86/events/intel/uncore.c (ffffffff81025dea)
Location: include/linux/pci.h:935
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/probe_roms.c (ffffffff810547a5)
Location: include/linux/pci.h:935
Inline: True
```
```
In drivers/pci/pci-driver.c (ffffffff818e5940)
Location: include/linux/pci.h:935
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_cleanup
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_bus_match
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
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
In arch/x86/events/intel/uncore.c (ffffffff81025d0b)
Location: include/linux/pci.h:940
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81055805)
Location: include/linux/pci.h:940
Inline: True
```
```
In drivers/pci/pci-driver.c (ffffffff81928f80)
Location: include/linux/pci.h:940
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_cleanup
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_bus_match
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
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
In arch/x86/events/intel/uncore.c (ffffffff8102be6b)
Location: include/linux/pci.h:961
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/probe_roms.c (ffffffff8105ca55)
Location: include/linux/pci.h:961
Inline: True
```
```
In drivers/pci/pci-driver.c (ffffffff81971780)
Location: include/linux/pci.h:961
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_cleanup
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_bus_match
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:new_id_store
```
</details>
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
