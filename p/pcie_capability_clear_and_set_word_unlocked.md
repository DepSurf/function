# Function: <code>pcie_capability_clear_and_set_word_unlocked</code>

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
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_clear_and_set_word_unlocked(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff819166bc)
Location: drivers/pci/access.c:500
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word_locked
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
ffffffff819165d0-ffffffff81916653: pcie_capability_clear_and_set_word_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_clear_and_set_word_unlocked(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e6ec)
Location: drivers/pci/access.c:500
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word_locked
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
ffffffff8195e600-ffffffff8195e681: pcie_capability_clear_and_set_word_unlocked (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
