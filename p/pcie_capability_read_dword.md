# Function: <code>pcie_capability_read_dword</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e530)
Location: drivers/pci/access.c:684
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8142e530-ffffffff8142e5c6: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479af0)
Location: drivers/pci/access.c:795
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81479af0-ffffffff81479b89: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149af80)
Location: drivers/pci/access.c:807
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8149af80-ffffffff8149b019: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4d40)
Location: drivers/pci/access.c:817
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-sysfs.c:max_link_width_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff814a4d40-ffffffff814a4df4: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3b20)
Location: drivers/pci/access.c:817
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-sysfs.c:max_link_width_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff814e3b20-ffffffff814e3bd4: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81513530)
Location: drivers/pci/access.c:450
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/pci-acpi.c:pciehp_is_native
```
**Symbols:**

```
ffffffff81513530-ffffffff815135cf: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528c70)
Location: drivers/pci/access.c:450
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81528c70-ffffffff81528d2e: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557d20)
Location: drivers/pci/access.c:450
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81557d20-ffffffff81557ddd: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81579330)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81579330-ffffffff815793ed: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e400)
Location: drivers/pci/access.c:437
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8161e400-ffffffff8161e4b9: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644c20)
Location: drivers/pci/access.c:437
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81644c20-ffffffff81644cdf: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816278c0)
Location: drivers/pci/access.c:437
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff816278c0-ffffffff8162797b: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816971c0)
Location: drivers/pci/access.c:437
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff816971c0-ffffffff8169727b: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8960)
Location: drivers/pci/access.c:442
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_check_latency
  - drivers/pci/pcie/aspm.c:pcie_aspm_check_latency
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff817b8960-ffffffff817b8a2b: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d33d0)
Location: drivers/pci/access.c:448
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_check_latency
  - drivers/pci/pcie/aspm.c:pcie_aspm_check_latency
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff818d33d0-ffffffff818d349b: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81916430)
Location: drivers/pci/access.c:448
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_check_latency
  - drivers/pci/pcie/aspm.c:pcie_aspm_check_latency
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81916430-ffffffff819164fe: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e460)
Location: drivers/pci/access.c:448
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pcie_get_speed_cap
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_reconfigure_ltr
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_check_latency
  - drivers/pci/pcie/aspm.c:pcie_aspm_check_latency
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8195e460-ffffffff8195e52e: pcie_capability_read_dword (STB_GLOBAL)
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
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db3a8)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffff8000106db3a8-ffff8000106db494: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0878048)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
c0878048-c0878114: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000852fe0)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
```
**Symbols:**

```
c000000000852fe0-c000000000853138: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b4154)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffe0004b4154-ffffffe0004b4204: pcie_capability_read_dword (STB_GLOBAL)
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
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d850)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8156d850-ffffffff8156d90d: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155bfc0)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8155bfc0-ffffffff8155c07d: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d080)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8156d080-ffffffff8156d13d: pcie_capability_read_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_read_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587b80)
Location: drivers/pci/access.c:441
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_get_aspm_reg
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81587b80-ffffffff81587c3d: pcie_capability_read_dword (STB_GLOBAL)
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
