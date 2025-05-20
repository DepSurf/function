# Function: <code>pci_reset_bridge_secondary_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_reset_bridge_secondary_bus(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81438200)
Location: drivers/pci/pci.c:3549
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_bus
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81438200-ffffffff81438210: pci_reset_bridge_secondary_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_reset_bridge_secondary_bus(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81484454)
Location: drivers/pci/pci.c:3870
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_bus
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81483ea0-ffffffff81483eb0: pci_reset_bridge_secondary_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_reset_bridge_secondary_bus(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5bb4)
Location: drivers/pci/pci.c:3908
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_bus
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff814a5600-ffffffff814a5610: pci_reset_bridge_secondary_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_reset_bridge_secondary_bus(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814af92e)
Location: drivers/pci/pci.c:4026
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff814af5f0-ffffffff814af600: pci_reset_bridge_secondary_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_reset_bridge_secondary_bus(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eeb81)
Location: drivers/pci/pci.c:4063
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv.c:aer_root_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff814eeb10-ffffffff814eeb20: pci_reset_bridge_secondary_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_reset_bridge_secondary_bus(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151e850)
Location: drivers/pci/pci.c:4310
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_parent_bus_reset
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff8151e850-ffffffff8151e874: pci_reset_bridge_secondary_bus (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
