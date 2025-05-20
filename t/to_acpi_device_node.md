# Function: <code>to_acpi_device_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct acpi_device *to_acpi_device_node(struct fwnode_handle *fwnode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814234c3)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81424b30)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81428689)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
```
```
In drivers/pci/probe.c (0)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81444e78)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81449456)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8144e8e0)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8145207d)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
```
```
In drivers/pci/pci-acpi.c (ffffffff814573f0)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_sleep_wake
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff81458105)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff8147c984)
Location: include/acpi/acpi_bus.h:404
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake
```
```
In drivers/acpi/bus.c (ffffffff8147eb51)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff8147ef33)
Location: include/acpi/acpi_bus.h:404
Inline: False
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_platform_notify_remove
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_platform_notify
```
```
In drivers/acpi/pci_irq.c (ffffffff81486ff8)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81487649)
Location: include/acpi/acpi_bus.h:404
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
```
```
In drivers/acpi/property.c (ffffffff8148a33a)
Location: include/acpi/acpi_bus.h:404
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_device_data_of_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
```
```
In drivers/acpi/fan.c (ffffffff814ab585)
Location: include/acpi/acpi_bus.h:404
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pci_slot.c (ffffffff814abfc8)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff814ac47d)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff814af94b)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff814bbbaa)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/dmaengine.c (ffffffff814bd9e3)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/dma/acpi-dma.c (ffffffff814be31e)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff814d19ca)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81529cee)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/base/property.c (ffffffff81551480)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_dma_attr
```
```
In drivers/mfd/mfd-core.c (ffffffff8158a8e6)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff815e0df7)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
```
```
In drivers/ata/libata-zpodd.c (ffffffff815e25c8)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff815e6c9f)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/usb/core/hub.c (ffffffff8160bfdf)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff8162080f)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8166254e)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff81678c55)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816cacf8)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8147c984-ffffffff8147c9a1: to_acpi_device_node (STB_LOCAL)
ffffffff8147ef33-ffffffff8147ef50: to_acpi_device_node (STB_LOCAL)
ffffffff81487649-ffffffff81487666: to_acpi_device_node (STB_LOCAL)
ffffffff8148a33a-ffffffff8148a357: to_acpi_device_node (STB_LOCAL)
ffffffff814ab585-ffffffff814ab5a2: to_acpi_device_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct acpi_device *to_acpi_device_node(struct fwnode_handle *fwnode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146c63d)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81471b03)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474c5f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/probe.c (ffffffff8147ce9a)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/quirks.c (ffffffff81490da9)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81495750)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8149b55f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fd99)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4357)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_sleep_wake
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814a4d85)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814cb371)
Location: include/acpi/acpi_bus.h:406
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
```
In drivers/acpi/bus.c (ffffffff814cd3c8)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814cd64d)
Location: include/acpi/acpi_bus.h:406
Inline: False
Direct callers:
  - drivers/acpi/glue.c:acpi_platform_notify_remove
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/pci_irq.c (ffffffff814d5c27)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d6401)
Location: include/acpi/acpi_bus.h:406
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/acpi/property.c (ffffffff814d91ff)
Location: include/acpi/acpi_bus.h:406
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/fan.c (ffffffff814fabc4)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pci_slot.c (ffffffff814fb2fa)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff814fb7c1)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff814ff266)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8150b623)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/acpi-dma.c (ffffffff8150dfde)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff815226ba)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8157d126)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff8158432b)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/amd_iommu.c:get_alias
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/base/property.c (ffffffff815a3430)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
```
```
In drivers/mfd/mfd-core.c (ffffffff815dfa9f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8163ba5d)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/ata/libata-zpodd.c (ffffffff8163c2a8)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff81644710)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_master_match
  - drivers/spi/spi.c:spi_register_master
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/usb/core/hub.c (ffffffff8166bb8f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff8168120d)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c279b)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff816ddc83)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:acpi_i2c_match_device
  - drivers/i2c/i2c-core.c:acpi_i2c_match_adapter
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172dca8)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff814cb371-ffffffff814cb399: to_acpi_device_node (STB_LOCAL)
ffffffff814cd64d-ffffffff814cd66c: to_acpi_device_node (STB_LOCAL)
ffffffff814d6401-ffffffff814d6429: to_acpi_device_node (STB_LOCAL)
ffffffff814d91ff-ffffffff814d9227: to_acpi_device_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct acpi_device *to_acpi_device_node(struct fwnode_handle *fwnode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148cd6d)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148e96d)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81493d9a)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814972df)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/probe.c (ffffffff8149e402)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/setup-bus.c (ffffffff82007e93)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814b2619)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814b7110)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814bd13f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c1919)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/pci-acpi.c (ffffffff814c6167)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_sleep_wake
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814c6c05)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814ed29d)
Location: include/acpi/acpi_bus.h:406
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
```
```
In drivers/acpi/bus.c (ffffffff814ef2f6)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814ef58e)
Location: include/acpi/acpi_bus.h:406
Inline: False
Direct callers:
  - drivers/acpi/glue.c:acpi_platform_notify_remove
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/pci_irq.c (ffffffff814f827f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f8a61)
Location: include/acpi/acpi_bus.h:406
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/acpi/property.c (ffffffff814fb98a)
Location: include/acpi/acpi_bus.h:406
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/fan.c (ffffffff8151d859)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pci_slot.c (ffffffff8151df8f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff8151e485)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff81521f60)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8152f843)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/acpi-dma.c (ffffffff8153a13e)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff8154eb9a)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815a95e6)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b165b)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/amd_iommu.c:get_alias
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/base/property.c (ffffffff815d1b40)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
```
```
In drivers/mfd/mfd-core.c (ffffffff8160c73f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8166cadd)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/ata/libata-zpodd.c (ffffffff8166d328)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff816757e0)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_master_match
  - drivers/spi/spi.c:spi_register_master
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/usb/core/hub.c (ffffffff8169988f)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816aef3d)
Location: include/acpi/acpi_bus.h:406
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f075b)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff8170dff8)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_acpi_match_device
  - drivers/i2c/i2c-core.c:i2c_acpi_match_adapter
  - drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81760c68)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff814ed29d-ffffffff814ed2c5: to_acpi_device_node (STB_LOCAL)
ffffffff814ef58e-ffffffff814ef5ad: to_acpi_device_node (STB_LOCAL)
ffffffff814f8a61-ffffffff814f8a89: to_acpi_device_node (STB_LOCAL)
ffffffff814fb98a-ffffffff814fb9b2: to_acpi_device_node (STB_LOCAL)
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
In kernel/irq/irqdomain.c (0)
Location: include/acpi/acpi_bus.h:409
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8149666d)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814970fe)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8149dcf9)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0f7f)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff820e8f5a)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814bc909)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814c1a51)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814c7910)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cbef8)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/pci-acpi.c (ffffffff814d0133)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814d0b75)
Location: include/acpi/acpi_bus.h:409
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814fa89c)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
```
In drivers/acpi/bus.c (ffffffff814fc2b3)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814fc933)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify_remove
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/pci_irq.c (ffffffff81506fdc)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815077bc)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/acpi/property.c (ffffffff8150b58c)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
```
```
In drivers/acpi/fan.c (ffffffff8152e8af)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pci_slot.c (ffffffff8152eff3)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff8152f633)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff81533a53)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815428f3)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/acpi-dma.c (ffffffff8154d998)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff8156310f)
Location: include/acpi/acpi_bus.h:409
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815bef2d)
Location: include/acpi/acpi_bus.h:409
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c8087)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/amd_iommu.c:get_alias
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/acpi/acpi_bus.h:409
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/acpi/acpi_bus.h:409
Inline: True
```
```
In drivers/base/property.c (ffffffff815e6900)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/base/dma-mapping.c (ffffffff815f6372)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_configure
```
```
In drivers/mfd/mfd-core.c (ffffffff8162081d)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff816810ea)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/ata/libata-zpodd.c (ffffffff81681968)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff81689f20)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/usb/core/hub.c (ffffffff816aebcd)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816c403f)
Location: include/acpi/acpi_bus.h:409
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705fe6)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f030)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724cdd)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_adapter
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727605)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81727d9c)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f4a8)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
</details>
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:699
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:699
Inline: True
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:699
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:699
Inline: True
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
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:699
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:699
Inline: True
```
</details>
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
</ul>
