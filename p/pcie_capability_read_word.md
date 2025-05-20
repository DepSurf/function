# Function: <code>pcie_capability_read_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e410)
Location: drivers/pci/access.c:649
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_get_minimum_link
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8142e410-ffffffff8142e4a6: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814799d0)
Location: drivers/pci/access.c:760
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_get_minimum_link
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff814799d0-ffffffff81479a69: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149ae60)
Location: drivers/pci/access.c:772
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_get_minimum_link
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8149ae60-ffffffff8149aef9: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4c00)
Location: drivers/pci/access.c:782
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_get_minimum_link
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff814a4c00-ffffffff814a4cb4: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e39e0)
Location: drivers/pci/access.c:782
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_get_minimum_link
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff814e39e0-ffffffff814e3a94: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81513410)
Location: drivers/pci/access.c:415
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_error_resume
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81513410-ffffffff815134af: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528b30)
Location: drivers/pci/access.c:415
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81528b30-ffffffff81528bee: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557c60)
Location: drivers/pci/access.c:415
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:program_hpp_type2
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81557c60-ffffffff81557d1d: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81579270)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81579270-ffffffff8157932d: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e340)
Location: drivers/pci/access.c:402
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8161e340-ffffffff8161e3f9: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644b60)
Location: drivers/pci/access.c:402
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81644b60-ffffffff81644c1f: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627800)
Location: drivers/pci/access.c:402
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81627800-ffffffff816278bb: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81697100)
Location: drivers/pci/access.c:402
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81697100-ffffffff816971bb: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8890)
Location: drivers/pci/access.c:407
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff817b8890-ffffffff817b895b: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d32f0)
Location: drivers/pci/access.c:413
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff818d32f0-ffffffff818d33bb: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81916350)
Location: drivers/pci/access.c:413
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word_locked
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_status
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81916350-ffffffff8191641e: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e380)
Location: drivers/pci/access.c:413
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word_locked
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_link_speed_mbps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_status
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aer.c:find_device_iter
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8195e380-ffffffff8195e44e: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dbff0)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffff8000106dbff0-ffff8000106dc0dc: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877eec)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
```
**Symbols:**

```
c0877eec-c0877fb8: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852e80)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
**Symbols:**

```
c000000000852e80-c000000000852fd8: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b402c)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffe0004b402c-ffffffe0004b40dc: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d790)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8156d790-ffffffff8156d84d: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bf00)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8155bf00-ffffffff8155bfbd: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156cfc0)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8156cfc0-ffffffff8156d07d: pcie_capability_read_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587ac0)
Location: drivers/pci/access.c:406
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_available
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_get_readrq
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci-sysfs.c:current_link_width_show
  - drivers/pci/pci-sysfs.c:current_link_speed_show
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81587ac0-ffffffff81587b7d: pcie_capability_read_word (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
