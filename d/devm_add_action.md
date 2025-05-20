# Function: <code>devm_add_action</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154f870)
Location: drivers/base/devres.c:710
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff8154f870-ffffffff8154f8c9: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1640)
Location: drivers/base/devres.c:710
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff815a1640-ffffffff815a1699: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815cfcf0)
Location: drivers/base/devres.c:711
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff815cfcf0-ffffffff815cfd49: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4850)
Location: drivers/base/devres.c:711
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff815e4850-ffffffff815e48a9: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164bb20)
Location: drivers/base/devres.c:711
Inline: False
Direct callers:
  - mm/hmm.c:hmm_devmem_add
  - mm/hmm.c:hmm_devmem_add
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8164bb20-ffffffff8164bb79: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687130)
Location: drivers/base/devres.c:715
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/hmm.c:hmm_devmem_add
  - mm/hmm.c:hmm_devmem_add
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81687130-ffffffff81687189: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a6cf0)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/hmm.c:hmm_devmem_add
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff816a6cf0-ffffffff816a6d49: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816dfdc0)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816dfdc0-ffffffff816dfe19: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704000)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81704000-ffffffff81704059: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817be430)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817be430-ffffffff817be489: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3180)
Location: drivers/base/devres.c:739
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817d3180-ffffffff817d31d9: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b6b90)
Location: drivers/base/devres.c:739
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - lib/bitmap.c:devm_bitmap_alloc
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:devm_pm_opp_set_regulators
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff817b6b90-ffffffff817b6be9: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840860)
Location: drivers/base/devres.c:728
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - lib/bitmap.c:devm_bitmap_alloc
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/regulator/devres.c:devm_regulator_irq_helper
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:devm_pm_opp_set_regulators
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81840860-ffffffff81840951: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81983970)
Location: drivers/base/devres.c:728
Inline: False
Direct callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - mm/memremap.c:devm_memremap_pages
  - lib/bitmap.c:devm_bitmap_alloc
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/regulator/devres.c:devm_regulator_irq_helper
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:devm_pm_opp_set_regulators
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81983970-ffffffff81983a96: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af1a10)
Location: drivers/base/devres.c:733
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - mm/memremap.c:devm_memremap_pages
  - lib/bitmap.c:devm_bitmap_alloc
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/regulator/devres.c:devm_regulator_irq_helper
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/opp/core.c:devm_pm_opp_set_config
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81af1a10-ffffffff81af1b33: devm_add_action (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108efab0)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
```
**Symbols:**

```
ffff8000108efab0-ffff8000108efb1c: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dd3c4)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
c09dd3c4-c09dd424: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000988f30)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
c000000000988f30-c000000000988fbc: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582452)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffe000582452-ffffffe0005824b2: devm_add_action (STB_GLOBAL)
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
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c9750)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816c9750-ffffffff816c97a9: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a4a80)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/nfit/core.c:acpi_nfit_add
  - drivers/acpi/nfit/core.c:acpi_nfit_add
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/device.c:dev_dax_probe
  - drivers/dax/device.c:dev_dax_probe
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816a4a80-ffffffff816a4ad9: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f7cc0)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816f7cc0-ffffffff816f7d19: devm_add_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devm_add_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712560)
Location: drivers/base/devres.c:723
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81712560-ffffffff817125b9: devm_add_action (STB_GLOBAL)
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
