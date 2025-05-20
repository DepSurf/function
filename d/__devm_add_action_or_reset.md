# Function: <code>__devm_add_action_or_reset</code>

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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81101d34)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
```
```
In kernel/reboot.c (ffffffff8113551c)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
```
In kernel/irq/irq_sim.c (ffffffff811b34a6)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
```
In mm/memremap.c (ffffffff814a3fad)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In block/blk-crypto-profile.c (ffffffff817c3b79)
Location: include/linux/device.h:369
Inline: True
```
```
In lib/bitmap.c (ffffffff8180c8c0)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8190594b)
Location: include/linux/device.h:369
Inline: True
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190d194)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff81912ee3)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/probe.c (ffffffff81918359)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/p2pdma.c (ffffffff8195f877)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/video/aperture.c (ffffffff81973043)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/device.h:369
Inline: False
```
```
In drivers/clk/clkdev.c (ffffffff81a3c249)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/dma/dmaengine.c (ffffffff81a4f1cc)
Location: include/linux/device.h:369
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a535d8)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/regulator/devres.c (ffffffff81a8f0c9)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
  - drivers/regulator/devres.c:_devm_regulator_get_enable
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81af0951)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/base/power/runtime.c (ffffffff81b4fda6)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/clock_ops.c (ffffffff81b5da2c)
Location: include/linux/device.h:369
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81ba24e6)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba61a8)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81badb5e)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dax/bus.c (ffffffff81bbbb9e)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81c24365)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca5ce2)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81ceb572)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d08d)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/rtc/class.c (ffffffff81d20d96)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2e619)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/opp/core.c (ffffffff81d9339f)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_config
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de67e7)
Location: include/linux/device.h:369
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81def2d7)
Location: include/linux/device.h:369
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff81dfb2f2)
Location: include/linux/device.h:369
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81dff39c)
Location: include/linux/device.h:369
Inline: True
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
In kernel/resource.c (ffffffff8110b4b3)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
```
```
In kernel/reboot.c (ffffffff81140570)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
```
In kernel/irq/irq_sim.c (ffffffff811c3326)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
```
In mm/memremap.c (ffffffff814d4e5d)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In block/blk-crypto-profile.c (ffffffff81808809)
Location: include/linux/device.h:394
Inline: True
```
```
In lib/bitmap.c (ffffffff818529d0)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8194d35b)
Location: include/linux/device.h:394
Inline: True
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81954e94)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff8195ae23)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/probe.c (ffffffff81960df9)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/p2pdma.c (ffffffff819a8edc)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/video/aperture.c (ffffffff819bd0b3)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/device.h:394
Inline: False
```
```
In drivers/clk/clkdev.c (ffffffff81a87b09)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/dma/dmaengine.c (ffffffff81a9ae6c)
Location: include/linux/device.h:394
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f388)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/regulator/devres.c (ffffffff81ae1939)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
  - drivers/regulator/devres.c:_devm_regulator_get_enable
```
```
In drivers/tty/serdev/core.c (ffffffff81b2fbd7)
Location: include/linux/device.h:394
Inline: True
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81b43eb1)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/base/power/runtime.c (ffffffff81ba8326)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb130c)
Location: include/linux/device.h:394
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81bf66a6)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa428)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c01e9e)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dax/bus.c (ffffffff81c10327)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/gpu/drm/drm_bridge.c (ffffffff81c80c40)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_bridge.c:devm_drm_bridge_add
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c41d)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:__devm_drm_dev_alloc
```
```
In drivers/gpu/drm/drm_panel.c (0)
Location: include/linux/device.h:394
Inline: False
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81cd5d55)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5a932)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81da0b92)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_create_intel_xhci_sw_pdev
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2dd9)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/rtc/class.c (ffffffff81dd6ac6)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de45c9)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/opp/core.c (ffffffff81e4adef)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_set_config
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c9c7)
Location: include/linux/device.h:394
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea5897)
Location: include/linux/device.h:394
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff81eb2942)
Location: include/linux/device.h:394
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81eb66a8)
Location: include/linux/device.h:394
Inline: True
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
