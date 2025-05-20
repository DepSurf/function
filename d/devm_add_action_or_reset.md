# Function: <code>devm_add_action_or_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815788e1)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff815ec13b)
Location: include/linux/device.h:688
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815a5071)
Location: include/linux/device.h:693
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff81618d2f)
Location: include/linux/device.h:693
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815b90f1)
Location: include/linux/device.h:693
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff8162ce73)
Location: include/linux/device.h:693
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81608208)
Location: include/linux/device.h:690
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8161fc31)
Location: include/linux/device.h:690
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff81695606)
Location: include/linux/device.h:690
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81641bba)
Location: include/linux/device.h:708
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81659a2b)
Location: include/linux/device.h:708
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff816d16c6)
Location: include/linux/device.h:708
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817a6d80)
Location: include/linux/device.h:708
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811fa631)
Location: include/linux/device.h:718
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/hmm.c (ffffffff812a6f4f)
Location: include/linux/device.h:718
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560fb9)
Location: include/linux/device.h:718
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165fcfa)
Location: include/linux/device.h:718
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816759db)
Location: include/linux/device.h:718
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff816f2d56)
Location: include/linux/device.h:718
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f553e)
Location: include/linux/device.h:718
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817ccc2f)
Location: include/linux/device.h:718
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812c281a)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81591165)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81695030)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816ab671)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff8172c1c8)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172edc9)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/dax/bus.c (ffffffff817402a1)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8180ca83)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4bee)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7bd0)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816ce3b1)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff81750418)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81753104)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175b492)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dax/bus.c (ffffffff817644a1)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8183da8c)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130a9be)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/pci/probe.c (ffffffff816204a2)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176bc50)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81782d51)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff8180eeb0)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81811c38)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818188a6)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dax/bus.c (ffffffff818245ee)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8191028c)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8194fcda)
Location: include/linux/device.h:254
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cbddd)
Location: include/linux/device.h:254
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131682e)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff816397ec)
Location: include/linux/device.h:257
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81646b30)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81786830)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8179a3a1)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff8181de20)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81820e28)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818279d6)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dax/bus.c (ffffffff81834b70)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/usb/dwc2/platform.c (ffffffff818e16c1)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81917bbf)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
```
In drivers/rtc/class.c (ffffffff8193f37b)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8195569a)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca7cf)
Location: include/linux/device.h:257
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131ca7e)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In block/keyslot-manager.c (ffffffff815a4fbf)
Location: include/linux/device.h:257
Inline: True
```
```
In lib/bitmap.c (ffffffff815a8c98)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8161d43c)
Location: include/linux/device.h:257
Inline: True
```
```
In drivers/pci/probe.c (ffffffff816294e4)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81709685)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a190)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8177ce81)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff8180108b)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804128)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180a942)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dax/bus.c (ffffffff81817d3c)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/spi/spi.c (ffffffff8186ca2d)
Location: include/linux/device.h:257
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c4911)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff818fb04e)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
```
In drivers/rtc/class.c (ffffffff81c16652)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192ccb4)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8193947a)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/opp/core.c (ffffffff81978c84)
Location: include/linux/device.h:257
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:devm_pm_opp_set_regulators
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af7df)
Location: include/linux/device.h:257
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81369dce)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In block/keyslot-manager.c (ffffffff8160da5f)
Location: include/linux/device.h:248
Inline: True
```
```
In lib/bitmap.c (ffffffff81611f38)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c8ec)
Location: include/linux/device.h:248
Inline: True
```
```
In drivers/pwm/core.c (ffffffff81694f53)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/probe.c (ffffffff81698ec4)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81785035)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/regulator/devres.c (ffffffff817b1eba)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817ee800)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81803051)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/base/power/runtime.c (ffffffff8184bb85)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/clock_ops.c (ffffffff81857b61)
Location: include/linux/device.h:248
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8188b49b)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e7f8)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81895202)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dax/bus.c (ffffffff818a238c)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
```
```
In drivers/spi/spi.c (ffffffff818fc8dd)
Location: include/linux/device.h:248
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195c271)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81999ebe)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
```
In drivers/rtc/class.c (ffffffff81d2506f)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cfe84)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff819ddb7a)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/opp/core.c (ffffffff81a21c04)
Location: include/linux/device.h:248
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:devm_pm_opp_set_regulators
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5dfbf)
Location: include/linux/device.h:248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81102b5c)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
```
In kernel/irq/irq_sim.c (ffffffff8116c696)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
```
In mm/memremap.c (ffffffff813e7acd)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In block/blk-crypto-profile.c (ffffffff816c2539)
Location: include/linux/device.h:249
Inline: True
```
```
In lib/bitmap.c (ffffffff816de269)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff817a9f0b)
Location: include/linux/device.h:249
Inline: True
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b05e4)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff817b5ba3)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/probe.c (ffffffff817ba369)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/device.h:249
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbc1e)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/regulator/devres.c (ffffffff818ed719)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192e86d)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81942871)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/base/power/runtime.c (ffffffff819918a6)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/clock_ops.c (ffffffff8199e11a)
Location: include/linux/device.h:249
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff819d47f6)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7e6a)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819dedca)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dax/bus.c (ffffffff819ebb84)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81a45cb5)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab6119)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81af6ebf)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b23186)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/rtc/class.c (ffffffff81ef0e66)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b31d59)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/opp/core.c (ffffffff81b8ac45)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:devm_pm_opp_set_regulators
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bce1c5)
Location: include/linux/device.h:249
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd4e15)
Location: include/linux/device.h:249
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff81be1322)
Location: include/linux/device.h:249
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81be4f7a)
Location: include/linux/device.h:249
Inline: True
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
In kernel/resource.c (ffffffff810f58ee)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
```
```
In kernel/reboot.c (ffffffff8112806c)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
```
In kernel/irq/irq_sim.c (ffffffff811a1696)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
```
In mm/memremap.c (ffffffff8146f7cd)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In block/blk-crypto-profile.c (ffffffff81783889)
Location: include/linux/device.h:250
Inline: True
```
```
In lib/bitmap.c (ffffffff817ce409)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff818c2a4b)
Location: include/linux/device.h:250
Inline: True
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff818ca104)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff818cff63)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/probe.c (ffffffff818d52a9)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/p2pdma.c (ffffffff8191c437)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/doe.c (ffffffff819204b2)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In drivers/video/aperture.c (ffffffff8192ed73)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/device.h:250
Inline: False
```
```
In drivers/clk/clkdev.c (ffffffff819f3b17)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a758)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/regulator/devres.c (ffffffff81a44f19)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
  - drivers/regulator/devres.c:_devm_regulator_get_enable
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8cb3a)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81aa5021)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/base/power/runtime.c (ffffffff81b01cb6)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/clock_ops.c (ffffffff81b0f96a)
Location: include/linux/device.h:250
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81b4f096)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52cfa)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5a5ee)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dax/bus.c (ffffffff81b68754)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81bcc795)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3ea89)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81c848b2)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5a19)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/rtc/class.c (ffffffff81cb9666)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc6979)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/opp/core.c (ffffffff81d2a1bf)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_config
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d788a5)
Location: include/linux/device.h:250
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81d80f25)
Location: include/linux/device.h:250
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff81d8cc02)
Location: include/linux/device.h:250
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81d910da)
Location: include/linux/device.h:250
Inline: True
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-host-common.c (ffff800010723134)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (ffff800011487bf4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff800011488ac4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e678)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a0160)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffff8000108b81cc)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffff80001094fe44)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffff800010953984)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095cb60)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dax/bus.c (ffff800010964304)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/usb/host/xhci-ext-caps.c (ffff800010a7bb74)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae1ab4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-vf610.c (c08738a4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
```
```
In drivers/pci/controller/pci-host-common.c (c08afde8)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (c1580128)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c1581930)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
```
```
In drivers/tty/serial/meson_uart.c (c09992dc)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (c0999eb8)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (c09b1a50)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/dax/bus.c (c0a3ad34)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad1584)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/net/ethernet/ti/cpts.c:cpts_create
```
```
In drivers/usb/host/xhci-ext-caps.c (c0b4f084)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
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
In mm/memremap.c (c00000000046e55c)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/pci/controller/pci-host-common.c (c00000000089184c)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/tty/serial/sccnxp.c (c00000000093dd54)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (c0000000009592bc)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (c0000000009fca90)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00ad4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0e1f4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dax/bus.c (c000000000a1b3a4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/usb/host/xhci-ext-caps.c (c000000000b538b8)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-host-common.c (ffffffe0004e6952)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055d274)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffe000568e7c)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffe0005c027c)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3210)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005cade2)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dax/bus.c (ffffffe0005d1694)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffe000692d5a)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cd1ce)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6655)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d630)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81693e01)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff81704b08)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817077f4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170fb82)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dax/bus.c (ffffffff81718b91)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817f5e3c)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812be03e)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815957f5)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/acpi/nfit/core.c (ffffffff815f8f68)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_add
  - drivers/acpi/nfit/core.c:acpi_nfit_add
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c720)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816717f1)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff816d8588)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816db274)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e3602)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb224)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
```
In drivers/nvdimm/blk.c (ffffffff816eeee7)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/nvdimm/blk.c:nd_blk_probe
```
```
In drivers/dax/bus.c (ffffffff816f10c1)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/dax/device.c (ffffffff816f1883)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/device.c:dev_dax_probe
  - drivers/dax/device.c:dev_dax_probe
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817bafdc)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cafde)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6be5)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816aba10)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816c2071)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff817438d8)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817465c4)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174e952)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dax/bus.c (ffffffff81757961)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8183290c)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812dbd3e)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c5e70)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816dc641)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/nvdimm/core.c (ffffffff8175ed28)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81761a04)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81769dd2)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dax/bus.c (ffffffff81772e01)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8184caec)
Location: include/linux/device.h:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
</ul>

## Differences
