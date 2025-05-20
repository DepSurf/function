# Function: <code>is_acpi_device_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814234c3)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81424b30)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81428689)
Location: include/acpi/acpi_bus.h:399
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
In drivers/pci/probe.c (ffffffff814315da)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/quirks.c (ffffffff81444e78)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81449456)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8144e8e0)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8145207d)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
```
```
In drivers/pci/pci-acpi.c (ffffffff814573f0)
Location: include/acpi/acpi_bus.h:399
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
Location: include/acpi/acpi_bus.h:399
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff8147c987)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:to_acpi_device_node
```
```
In drivers/acpi/bus.c (ffffffff8147eb51)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff8147ef36)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/glue.c:to_acpi_device_node
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/pci_irq.c (ffffffff81486ff8)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8148764c)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:to_acpi_device_node
```
```
In drivers/acpi/property.c (ffffffff8148a33d)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/property.c:to_acpi_device_node
```
```
In drivers/acpi/fan.c (ffffffff814ab588)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/fan.c:to_acpi_device_node
```
```
In drivers/acpi/pci_slot.c (ffffffff814abfc8)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff814ac47d)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff814af94b)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff814bbbaa)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/dmaengine.c (ffffffff814bd9e3)
Location: include/acpi/acpi_bus.h:399
Inline: True
```
```
In drivers/dma/acpi-dma.c (ffffffff814be31e)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff814d19ca)
Location: include/acpi/acpi_bus.h:399
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81529cee)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff815354ce)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/property.c (ffffffff81551480)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_dma_attr
```
```
In drivers/mfd/mfd-core.c (ffffffff8158a8e6)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff815e0df7)
Location: include/acpi/acpi_bus.h:399
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
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff815e6c9f)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/usb/core/hub.c (ffffffff8160bfdf)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff8162080f)
Location: include/acpi/acpi_bus.h:399
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8166254e)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff81678c55)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816cacf8)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(struct fwnode_handle *fwnode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146c63d)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81471b03)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474c5f)
Location: include/acpi/acpi_bus.h:401
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
In drivers/pci/probe.c (ffffffff8147ccfd)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/quirks.c (ffffffff81490da9)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81495750)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8149b55f)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fd99)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4357)
Location: include/acpi/acpi_bus.h:401
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
Location: include/acpi/acpi_bus.h:401
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814cb372)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:to_acpi_device_node
```
```
In drivers/acpi/bus.c (ffffffff814cd3c8)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814cd62c)
Location: include/acpi/acpi_bus.h:401
Inline: False
Direct callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:to_acpi_device_node
```
```
In drivers/acpi/pci_irq.c (ffffffff814d5c27)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d6402)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:to_acpi_device_node
```
```
In drivers/acpi/property.c (ffffffff814d9200)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/property.c:to_acpi_device_node
```
```
In drivers/acpi/fan.c (ffffffff814fa91b)
Location: include/acpi/acpi_bus.h:401
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pci_slot.c (ffffffff814fb2fa)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff814fb7c1)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff814ff275)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8150b623)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/dmaengine.c (ffffffff8150d4a9)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/dma/acpi-dma.c (ffffffff8150dfde)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff815226ba)
Location: include/acpi/acpi_bus.h:401
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8157d126)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff8158432e)
Location: include/acpi/acpi_bus.h:401
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
In drivers/iommu/intel-iommu.c (ffffffff81589ef6)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/property.c (ffffffff815a3430)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
```
```
In drivers/mfd/mfd-core.c (ffffffff815dfa9f)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8163ba5d)
Location: include/acpi/acpi_bus.h:401
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
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff81644710)
Location: include/acpi/acpi_bus.h:401
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
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff8168120d)
Location: include/acpi/acpi_bus.h:401
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c279b)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff816ddc5d)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
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
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff814cd62c-ffffffff814cd64d: is_acpi_device_node (STB_LOCAL)
ffffffff814fa91b-ffffffff814fa93c: is_acpi_device_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(struct fwnode_handle *fwnode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148cd6d)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148e96d)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81493d9a)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814972df)
Location: include/acpi/acpi_bus.h:401
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
In drivers/pci/probe.c (ffffffff8149e25d)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/setup-bus.c (ffffffff82007e93)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814b2619)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814b7110)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814bd13f)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c1919)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/pci-acpi.c (ffffffff814c6167)
Location: include/acpi/acpi_bus.h:401
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
Location: include/acpi/acpi_bus.h:401
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814ed29e)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:to_acpi_device_node
```
```
In drivers/acpi/bus.c (ffffffff814ef2f6)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814ef56d)
Location: include/acpi/acpi_bus.h:401
Inline: False
Direct callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:to_acpi_device_node
```
```
In drivers/acpi/pci_irq.c (ffffffff814f827f)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f8a62)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:to_acpi_device_node
```
```
In drivers/acpi/property.c (ffffffff814fb98b)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/property.c:to_acpi_device_node
```
```
In drivers/acpi/fan.c (ffffffff8151d58c)
Location: include/acpi/acpi_bus.h:401
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pci_slot.c (ffffffff8151df8f)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff8151e485)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff81521f6f)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8152f843)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/dmaengine.c (ffffffff815395d9)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/dma/acpi-dma.c (ffffffff8153a13e)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff8154eb9a)
Location: include/acpi/acpi_bus.h:401
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815a95e6)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b165e)
Location: include/acpi/acpi_bus.h:401
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
In drivers/iommu/intel-iommu.c (ffffffff815b75a6)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff815cdc7d)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/base/property.c (ffffffff815d1b40)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
```
```
In drivers/mfd/mfd-core.c (ffffffff8160c73f)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8166cadd)
Location: include/acpi/acpi_bus.h:401
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
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff816757e0)
Location: include/acpi/acpi_bus.h:401
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
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816aef3d)
Location: include/acpi/acpi_bus.h:401
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f075b)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff8170dfd2)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_acpi_match_device
  - drivers/i2c/i2c-core.c:i2c_acpi_match_adapter
  - drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81760c68)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff814ef56d-ffffffff814ef58e: is_acpi_device_node (STB_LOCAL)
ffffffff8151d58c-ffffffff8151d5ad: is_acpi_device_node (STB_LOCAL)
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
In kernel/irq/irqdomain.c (ffffffff810ec693)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8149666d)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814970fe)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8149dcf9)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0f7f)
Location: include/acpi/acpi_bus.h:404
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
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814bc909)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814c1a51)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814c7910)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cbef8)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/pci-acpi.c (ffffffff814d0133)
Location: include/acpi/acpi_bus.h:404
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
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814fa89c)
Location: include/acpi/acpi_bus.h:404
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
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814fc933)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify_remove
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/pci_irq.c (ffffffff81506fdc)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815077bc)
Location: include/acpi/acpi_bus.h:404
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
In drivers/acpi/property.c (ffffffff8150b575)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
```
```
In drivers/acpi/fan.c (ffffffff8152e8af)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pci_slot.c (ffffffff8152eff3)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff8152f633)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff81533a53)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815428f3)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/dmaengine.c (ffffffff8154cef9)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/dma/acpi-dma.c (ffffffff8154d998)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff8156310f)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815bef2d)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c8087)
Location: include/acpi/acpi_bus.h:404
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
In drivers/iommu/intel-iommu.c (ffffffff815cd420)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff815e26ad)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/base/property.c (ffffffff815e6900)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/base/dma-mapping.c (ffffffff815f635c)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_configure
```
```
In drivers/mfd/mfd-core.c (ffffffff8162081d)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff816810ea)
Location: include/acpi/acpi_bus.h:404
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
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff81689f20)
Location: include/acpi/acpi_bus.h:404
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
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816c403f)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705fe6)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f030)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724cdd)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_adapter
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817274c8)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81727d9c)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f4a8)
Location: include/acpi/acpi_bus.h:404
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In drivers/platform/x86/silead_dmi.c (ffffffff81798a2c)
Location: include/acpi/acpi_bus.h:404
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154e475)
Location: drivers/acpi/property.c:1299
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify_remove
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/tty/serdev/core.c:serdev_controller_add
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
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/base/dma-mapping.c:dma_configure
  - drivers/base/dma-mapping.c:dma_configure
  - drivers/base/dma-mapping.c:dma_configure
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
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
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8154dc80-ffffffff8154dca8: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815843f5)
Location: drivers/acpi/property.c:1307
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
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
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify_remove
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
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
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815845c0-ffffffff815845e8: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159cffd)
Location: drivers/acpi/property.c:1348
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
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
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8159c730-ffffffff8159c758: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce795)
Location: drivers/acpi/property.c:1374
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
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
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/soundwire/bus.c:sdw_add_bus_master
  - drivers/soundwire/slave.c:sdw_acpi_find_slaves
```
**Symbols:**

```
ffffffff815cdba0-ffffffff815cdbc8: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815efa15)
Location: drivers/acpi/property.c:1374
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
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
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815eee20-ffffffff815eee48: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169bc7e)
Location: drivers/acpi/property.c:1422
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_regions
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/iommu/amd/iommu.c:get_devid
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff8169b060-ffffffff8169b088: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8a9e)
Location: drivers/acpi/property.c:1437
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_regions
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff816b7ea0-ffffffff816b7ec8: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169aa3e)
Location: drivers/acpi/property.c:1416
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff81699e50-ffffffff81699e78: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8171089e)
Location: drivers/acpi/property.c:1411
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_device_notify_remove
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff8170fcf0-ffffffff8170fd18: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff818400f3)
Location: drivers/acpi/property.c:1448
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr
  - drivers/acpi/property.c:acpi_fwnode_device_dma_supported
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pci/pci.c:pci_pr3_present
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pcie/edr.c:pci_acpi_remove_edr_notifier
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/acpi/device_pm.c:acpi_dev_state_d0
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_device_notify_remove
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/reset/core.c:__device_reset
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:check_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_handle
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_waive_d0_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff8183e880-ffffffff8183e8b4: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819766f3)
Location: drivers/acpi/property.c:1619
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr
  - drivers/acpi/property.c:acpi_fwnode_device_dma_supported
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pci/pci.c:pci_pr3_present
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pcie/edr.c:pci_acpi_remove_edr_notifier
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/acpi/device_pm.c:acpi_dev_state_d0
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_device_notify_remove
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/reset/core.c:__device_reset
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:check_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_handle
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_waive_d0_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff81974840-ffffffff81974874: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bc8d3)
Location: drivers/acpi/property.c:1607
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr
  - drivers/acpi/property.c:acpi_fwnode_device_dma_supported
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pci/pci.c:pci_pr3_present
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pcie/edr.c:pci_acpi_remove_edr_notifier
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_config_space_access
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/acpi/device_pm.c:acpi_dev_state_d0
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_device_notify_remove
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/reset/core.c:__device_reset
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_handle
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_waive_d0_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff819bb060-ffffffff819bb094: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a071c3)
Location: drivers/acpi/property.c:1675
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr
  - drivers/acpi/property.c:acpi_fwnode_device_dma_supported
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_parse_string_ref
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pci/pci.c:pci_pr3_present
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pcie/edr.c:pci_acpi_remove_edr_notifier
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_config_space_access
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/acpi/device_pm.c:acpi_dev_state_d0
  - drivers/acpi/device_pm.c:acpi_storage_d3
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_device_notify_remove
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration
  - drivers/acpi/ac.c:acpi_ac_probe
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/reset/core.c:__device_reset
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
  - drivers/base/core.c:device_match_acpi_handle
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/gpu/drm/drm_sysfs.c:drm_connector_acpi_find_companion
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_waive_d0_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/platform/x86/amd/wbrf.c:amd_wbrf_retrieve_freq_band
  - drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_supported_consumer
  - drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_supported_producer
  - drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_add_remove
```
**Symbols:**

```
ffffffff81a05890-ffffffff81a058c4: is_acpi_device_node (STB_GLOBAL)
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
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077a860)
Location: drivers/acpi/property.c:1374
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
  - drivers/irqchip/irq-mbigen.c:mbigen_domain_translate
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_translate
  - drivers/bus/hisi_lpc.c:hisi_lpc_remove
  - drivers/bus/hisi_lpc.c:hisi_lpc_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_remove
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
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
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
```
**Symbols:**

```
ffff800010779ae8-ffff800010779b3c: is_acpi_device_node (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815de6a5)
Location: drivers/acpi/property.c:1374
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
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
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815ddab0-ffffffff815ddad8: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9ce5)
Location: drivers/acpi/property.c:1374
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
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
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff815c90f0-ffffffff815c9118: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3cf5)
Location: drivers/acpi/property.c:1374
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
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
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815e3100-ffffffff815e3128: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fdbb5)
Location: drivers/acpi/property.c:1374
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/pci-driver.c:pci_dma_configure
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume
  - drivers/acpi/device_pm.c:acpi_dev_suspend
  - drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
  - drivers/acpi/bus.c:acpi_companion_match
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/container.c:acpi_container_offline
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/iommu/intel-iommu.c:device_to_iommu
  - drivers/base/core.c:device_match_acpi_dev
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
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
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffffffff815fcfc0-ffffffff815fcfe8: is_acpi_device_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
