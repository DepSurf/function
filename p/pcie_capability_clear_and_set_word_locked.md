# Function: <code>pcie_capability_clear_and_set_word_locked</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word_locked(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81916670)
Location: drivers/pci/access.c:517
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
```
**Symbols:**

```
ffffffff81916670-ffffffff81916721: pcie_capability_clear_and_set_word_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word_locked(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e6a0)
Location: drivers/pci/access.c:516
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
```
**Symbols:**

```
ffffffff8195e6a0-ffffffff8195e74f: pcie_capability_clear_and_set_word_locked (STB_GLOBAL)
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
