# Function: <code>pcie_capability_clear_and_set_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e4b0)
Location: drivers/pci/access.c:736
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff8142e4b0-ffffffff8142e529: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479a70)
Location: drivers/pci/access.c:847
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff81479a70-ffffffff81479ae9: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149af00)
Location: drivers/pci/access.c:859
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff8149af00-ffffffff8149af79: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4cc0)
Location: drivers/pci/access.c:869
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_flr
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff814a4cc0-ffffffff814a4d39: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3aa0)
Location: drivers/pci/access.c:869
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_flr
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff814e3aa0-ffffffff814e3b19: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815134b0)
Location: drivers/pci/access.c:502
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_flr
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff815134b0-ffffffff8151352b: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528bf0)
Location: drivers/pci/access.c:502
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff81528bf0-ffffffff81528c6b: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557e50)
Location: drivers/pci/access.c:502
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff81557e50-ffffffff81557ecb: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81579460)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff81579460-ffffffff815794db: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e550)
Location: drivers/pci/access.c:489
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
```
**Symbols:**

```
ffffffff8161e550-ffffffff8161e5cb: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644d80)
Location: drivers/pci/access.c:489
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
```
**Symbols:**

```
ffffffff81644d80-ffffffff81644dfb: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627a20)
Location: drivers/pci/access.c:489
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
ffffffff81627a20-ffffffff81627a97: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81697320)
Location: drivers/pci/access.c:489
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
ffffffff81697320-ffffffff81697397: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8ae0)
Location: drivers/pci/access.c:494
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
ffffffff817b8ae0-ffffffff817b8b63: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d3570)
Location: drivers/pci/access.c:500
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
ffffffff818d3570-ffffffff818d35f3: pcie_capability_clear_and_set_word (STB_GLOBAL)
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
In drivers/pci/probe.c (ffffffff8191a0db)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8191febb)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193abb0)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
```
In drivers/pci/pcie/aspm.c (ffffffff8193c549)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/aer.c (ffffffff8193f666)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
```
```
In drivers/pci/pcie/pme.c (ffffffff81941571)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/pci-acpi.c (ffffffff81944fdd)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8194b8fd)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819547a5)
Location: include/linux/pci.h:1242
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
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
In drivers/pci/probe.c (ffffffff819624db)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8196809b)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983a10)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
```
```
In drivers/pci/pcie/aspm.c (ffffffff81984dad)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
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
```
```
In drivers/pci/pcie/aer.c (ffffffff819891bb)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a7d1)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/pci-acpi.c (ffffffff8198e30d)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81996fcd)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199dc35)
Location: include/linux/pci.h:1270
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dc0e0)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffff8000106dc0e0-ffff8000106dc180: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877fb8)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_relax_enable
```
**Symbols:**

```
c0877fb8-c0878048: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000853240)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
**Symbols:**

```
c000000000853240-c0000000008532fc: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b40dc)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffe0004b40dc-ffffffe0004b4154: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d980)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff8156d980-ffffffff8156d9fb: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155c0f0)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff8155c0f0-ffffffff8155c16b: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d1b0)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff8156d1b0-ffffffff8156d22b: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev *dev, int pos, u16 clear, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587cb0)
Location: drivers/pci/access.c:493
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_config_aspm_link
  - drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
**Symbols:**

```
ffffffff81587cb0-ffffffff81587d2b: pcie_capability_clear_and_set_word (STB_GLOBAL)
```
</details>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
