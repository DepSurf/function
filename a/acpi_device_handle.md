# Function: <code>acpi_device_handle</code>

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
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814234d1)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81424baf)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81428693)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
```
```
In drivers/pci/quirks.c (ffffffff81444e82)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81449475)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8144e97c)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452bd4)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/pci-acpi.c (ffffffff8145794a)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff81458112)
Location: include/linux/acpi.h:47
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff81487002)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814877c8)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/acpi/pci_slot.c (ffffffff814abfd2)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/dma/dmaengine.c (ffffffff814bd9ee)
Location: include/linux/acpi.h:47
Inline: True
```
```
In drivers/xen/pci.c (ffffffff814d1a58)
Location: include/linux/acpi.h:47
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81529d00)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/ata/libata-acpi.c (ffffffff815e0e01)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
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
In drivers/spi/spi.c (ffffffff815e8f8d)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/usb/core/hub.c (ffffffff8160bfe9)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81662558)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff8167b0e1)
Location: include/linux/acpi.h:47
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146e917)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474b01)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/quirks.c (ffffffff81490dbb)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81495764)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8149b58b)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149f498)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4c3d)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814a4d9b)
Location: include/linux/acpi.h:49
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff814d5c45)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d64e0)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/acpi/pci_slot.c (ffffffff814fb30c)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/xen/pci.c (ffffffff8152273c)
Location: include/linux/acpi.h:49
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8157d144)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/ata/libata-acpi.c (ffffffff8163ba7e)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/spi/spi.c (ffffffff8164767b)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/usb/core/hub.c (ffffffff8166bba2)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c27ad)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff816ddcf5)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:acpi_i2c_match_adapter
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
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
In drivers/gpio/gpiolib.c (ffffffff81490977)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81497181)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff82007ea5)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814b262b)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814b7124)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814bd16b)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff814c6abd)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814c6c1b)
Location: include/linux/acpi.h:49
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff814f829d)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f8b40)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/acpi/pci_slot.c (ffffffff8151dfa1)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/xen/pci.c (ffffffff8154ec1c)
Location: include/linux/acpi.h:49
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815a9604)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:49
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8166cafe)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/spi/spi.c (ffffffff81678776)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/usb/core/hub.c (ffffffff816998a2)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f076d)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff8170e099)
Location: include/linux/acpi.h:49
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_acpi_match_adapter
  - drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core.c:i2c_acpi_do_lookup
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
In kernel/irq/irqdomain.c (ffffffff810ec77f)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff8149a126)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0e21)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff820e8f6c)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814bc91b)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814c1a65)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814c793c)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff814d0a2e)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814d0b8c)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff81507012)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81507acb)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/acpi/pci_slot.c (ffffffff8152f007)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/xen/pci.c (ffffffff815633d1)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815bef8e)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8168110b)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/spi/spi.c (ffffffff8168cecc)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/hub.c (ffffffff816aebe3)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705ff8)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724d05)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_adapter
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8172771b)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81727dca)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In kernel/irq/irqdomain.c (ffffffff810f5047)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff814d8410)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814df7e9)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff826f1d7f)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814fccd9)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81501c77)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81507ebc)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff81510c28)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff81510dc8)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff8154925a)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81549f31)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/acpi/pci_slot.c (ffffffff8158fcd9)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815a02d5)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff815c7422)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8160994e)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81625516)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81694b99)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81694e97)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff816ea95d)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/spi/spi.c (ffffffff816f66a9)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/hub.c (ffffffff8171a1ca)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817771be)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817961bf)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798d14)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff8179940a)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In kernel/irq/irqdomain.c (ffffffff810fd427)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff8150788d)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150eba5)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff8271bd10)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff8152d8d9)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81538d9c)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff81545d70)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff81545f68)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff8157f3ba)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81580147)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/pci_slot.c (ffffffff815c7089)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815d7f65)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff815ffc8b)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8164316e)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8165f83f)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff816d0c6f)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff816d0f5d)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff81727363)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffffffff81731af9)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/hub.c (ffffffff81758f6a)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7f21)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8d09)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817dbcc2)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff817dc16a)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd7d0)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
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
In kernel/irq/irqdomain.c (ffffffff81108ec7)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff8151c11d)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81524205)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff828d3c89)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81541f62)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81544729)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8155012c)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff8155c506)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/acpi/pci_irq.c (ffffffff815970da)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81598027)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/pci_slot.c (ffffffff815e0649)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815f1875)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff8161ad5b)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81661466)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8167dcff)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff816f230f)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff816f25fd)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff81749b43)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffffffff817544e9)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/hub.c (ffffffff8177d4da)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817de620)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ffea9)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802a51)
Location: include/linux/acpi.h:50
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff8180311a)
Location: include/linux/acpi.h:50
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In kernel/irq/irqdomain.c (ffffffff811124a7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff8154a3f6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81552765)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff828edcdf)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81571ab6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81573c95)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8157ff7c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff8158c826)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815c6b4b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff815c828a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c90c8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/property.c (ffffffff815ce163)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/pci_slot.c (ffffffff816121d9)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81623772)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff8164eabd)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81696e98)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816b4a3d)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8172b88f)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8172bb5d)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff817859be)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffffffff8178fda9)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff817ba03a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8181f08b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8184109e)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843e21)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff818445ea)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
```
In drivers/soundwire/bus.c (ffffffff818c0fa3)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/soundwire/bus.c:sdw_add_bus_master
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
In kernel/irq/irqdomain.c (ffffffff8111e737)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff8156b606)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81573da5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff828f6e20)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81593036)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff815952e5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815a19bc)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff815ae446)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815e7d7b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff815e94aa)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815ea3e8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/property.c (ffffffff815ef3e3)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/pci_slot.c (ffffffff81633689)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81645262)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff81671187)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/tty/serdev/core.c (ffffffff816b9a28)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816d771d)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8174fadf)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8174fdad)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff817a95fe)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffffffff817b3ae0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff817ea88a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185034b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff818729fe)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875791)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81875f1a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In drivers/gpio/gpiolib.c (ffffffff8160da57)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81618353)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_regions
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff82d0dc6b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff816414c6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81643c05)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8164a34c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff816579cd)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
```
```
In drivers/acpi/pci_root.c (ffffffff81693717)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff816950a5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81695af8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
```
```
In drivers/acpi/evged.c (ffffffff816995e7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/property.c (ffffffff8169b5f3)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/pci_slot.c (ffffffff816e0529)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff816f2d52)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtcrc.c (ffffffff816f30d2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff816f3140)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff816f34b2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff816f37c2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff816f3912)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f3ab2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff817217ed)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/tty/serdev/core.c (ffffffff8176e01f)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8178bbed)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8180e22f)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8180e4fd)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff8186f0a7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff8187b164)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff818b9cdc)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81946b8c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81948091)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff8194a63a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In drivers/gpio/gpiolib.c (ffffffff81634367)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163ed53)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_regions
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff82ffb675)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff816679b6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff8166a065)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8166ec3c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff81677e2d)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
```
```
In drivers/acpi/pci_root.c (ffffffff816b1207)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff816b22f5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b2c88)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
```
```
In drivers/acpi/evged.c (ffffffff816b6707)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/pci_slot.c (ffffffff816fe389)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff8170fef2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtcrc.c (ffffffff81710272)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff817102e0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81710652)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff81710962)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff81710a92)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81710c32)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff8173e4c3)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/tty/serdev/core.c (ffffffff817889e2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff817a218e)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8181ce3f)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8181d0bd)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff8187dd77)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81889e0f)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff818c85bc)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194caec)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194de91)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff819501ba)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81622775)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff83206405)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81649ec6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff8164c512)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8165117c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff8165a512)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
```
```
In drivers/acpi/pci_root.c (ffffffff816933d7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff81694665)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81694f18)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
```
In drivers/acpi/evged.c (ffffffff816987b7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/pci_slot.c (ffffffff816e00a9)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff816f17c2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtcrc.c (ffffffff816f1b42)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff816f1bb0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff816f1f22)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff816f2222)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff816f2362)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f2502)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff81721fdf)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/tty/serdev/core.c (ffffffff8176c534)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81784e80)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff818001cf)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8180044d)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff81860502)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff8186c813)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff818abc0c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191ff22)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8193065c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819319f8)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff8193404a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81691ef5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff832ee117)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff816bba76)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff816be5a4)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff816c2ebc)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff816cc852)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
```
```
In drivers/acpi/glue.c (ffffffff816fec27)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_device_notify
```
```
In drivers/acpi/pci_root.c (ffffffff81708f27)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff8170a375)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170ac08)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
```
In drivers/acpi/evged.c (ffffffff8170e537)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/pci_slot.c (ffffffff817582e9)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff8176b8c2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtcrc.c (ffffffff8176bc62)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff8176bcd0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff8176c0f2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff8176c462)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff8176c5a2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8176c742)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff817a0e1d)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/tty/serdev/core.c (ffffffff817f1c74)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8180b9bf)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8188a5bf)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8188a84d)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff818ef2c2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff818fc6b5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff8190b77e)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81940c2c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2bc2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d393c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d4cd8)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff819d747a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In drivers/gpio/gpiolib-acpi.c (ffffffff817b14ad)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
```
In drivers/pci/setup-bus.c (ffffffff834a601a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff817e03a2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff817e44d4)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff817e88e4)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff817f3082)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
```
```
In drivers/acpi/glue.c (ffffffff8182c59e)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_device_notify
```
```
In drivers/acpi/pci_root.c (ffffffff818372f7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff818386ca)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8183a25f)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
```
In drivers/acpi/evged.c (ffffffff8183cf23)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff8188b8a9)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff818a05e2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtcrc.c (ffffffff818a0a02)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff818a0a92)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff818a0f92)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff818a1382)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff818a14f2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff818a16ef)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff818dac70)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/reset/core.c (ffffffff818ef4e7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
```
```
In drivers/tty/serdev/core.c (ffffffff819323da)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8194bf1e)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/core.c (ffffffff819756c6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/base/core.c:device_match_acpi_handle
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/physical_location.c (ffffffff819b4880)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff819d3b95)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff81a414d2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81a4dd47)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff81a5f042)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
```
In drivers/usb/core/hub.c (ffffffff81a98e3c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b23018)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b36094)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37661)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81b3a6d5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
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
In drivers/gpio/gpiolib-acpi.c (ffffffff818caefd)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
```
In drivers/pci/setup-bus.c (ffffffff83edc7de)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81903342)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81908b74)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8190e284)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff8191b812)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
```
```
In drivers/acpi/glue.c (ffffffff8195f1be)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_device_notify
```
```
In drivers/acpi/pci_root.c (ffffffff8196c55a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff8196da5a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8196f8ff)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
```
In drivers/acpi/evged.c (ffffffff819729b3)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff819d2619)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff819e9ad2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtcrc.c (ffffffff819e9f62)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff819ea012)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff819ea592)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff819ea9f2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff819eabd2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff819eade4)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff81a2dc40)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/reset/core.c (ffffffff81a471f7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
```
```
In drivers/tty/serdev/core.c (ffffffff81a90eb4)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81aaffde)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/core.c (ffffffff81ae11a6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/base/core.c:device_match_acpi_handle
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/physical_location.c (ffffffff81b2983b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81b4e285)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff81bc7742)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81bd8381)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff81bea3b2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
```
In drivers/usb/core/hub.c (ffffffff81c1cd6c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb58a8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccb384)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81cccb41)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81cd0295)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8190e00d)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff837022de)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff819469e2)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_config_space_access
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff8194c1c4)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81951904)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff8195ee22)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
```
```
In drivers/acpi/glue.c (ffffffff819a55aa)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_device_notify
```
```
In drivers/acpi/pci_root.c (ffffffff819b2ad9)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff819b3f8a)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819b5eb7)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
```
In drivers/acpi/evged.c (ffffffff819b9083)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/property.c (0)
Location: include/linux/acpi.h:40
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff81a19c39)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff81a321f2)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtcrc.c (ffffffff81a32682)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81a32732)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81a32cb2)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff81a33112)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff81a332f2)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a334f6)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff81a773e0)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/reset/core.c (ffffffff81a91397)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
```
```
In drivers/tty/serdev/core.c (ffffffff81adc6c3)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81afbe31)
Location: include/linux/acpi.h:40
Inline: True
```
```
In drivers/base/core.c (ffffffff81b2f3f6)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/base/core.c:device_match_acpi_handle
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:40
Inline: True
```
```
In drivers/base/physical_location.c (ffffffff81b799eb)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81ba16e5)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff81c1f2d2)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81c2ed87)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff81c427e3)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
```
In drivers/usb/core/hub.c (ffffffff81c83c7c)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1cf18)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d330f4)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d348a1)
Location: include/linux/acpi.h:40
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81d37cd5)
Location: include/linux/acpi.h:40
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193ed04)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81955d9d)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
```
In drivers/pci/setup-bus.c (ffffffff8197efbe)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff8198fd12)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_config_space_access
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81995494)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8199ad64)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff819a8482)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
```
```
In drivers/acpi/glue.c (ffffffff819edf2a)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_device_notify
```
```
In drivers/acpi/mipi-disco-img.c (ffffffff819f29f5)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
```
```
In drivers/acpi/pci_root.c (ffffffff819fcfe9)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff819fe6a9)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81a00525)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
```
In drivers/acpi/evged.c (ffffffff81a036c3)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/property.c (0)
Location: include/linux/acpi.h:52
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff81a64f39)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/intel_pmic_bytcrc.c (ffffffff81a7d662)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtcrc.c (ffffffff81a7daf2)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81a7dba2)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_bxtwc.c (ffffffff81a7e122)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtwc.c (ffffffff81a7e582)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe
```
```
In drivers/acpi/pmic/intel_pmic_chtdc_ti.c (ffffffff81a7e762)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a7e966)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff81ac95f0)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/reset/core.c (ffffffff81ae3a87)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f9e3)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81b4f4cf)
Location: include/linux/acpi.h:52
Inline: True
```
```
In drivers/base/core.c (ffffffff81b86bf6)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/base/core.c:device_match_acpi_handle
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:52
Inline: True
```
```
In drivers/base/physical_location.c (ffffffff81bcd91b)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81bf5875)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff81c74432)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81ce1b21)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff81cf7ea3)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
```
In drivers/usb/core/hub.c (ffffffff81d3867c)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2c68)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de9144)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81dea951)
Location: include/linux/acpi.h:52
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81dedf55)
Location: include/linux/acpi.h:52
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
```
</details>
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
In arch/arm64/kernel/pci.c (ffff8000100a7c60)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/pci.c:pcibios_root_bridge_prepare
```
```
In kernel/irq/irqdomain.c (ffff800010183f30)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff800011476250)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
```
```
In drivers/gpio/gpiolib.c (ffff8000106bede4)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cbe14)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffff800011478cd0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffff8000106f90e0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffff80001070a178)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffff8000107187b8)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_root.c (ffff800010775600)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffff8000107765ec)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/evged.c (ffff800010778f48)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/property.c (ffff80001077a068)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/pci_slot.c (ffff8000107a1c58)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffff8000107b1008)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffff80001083c5cc)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/tty/serdev/core.c (ffff8000108a9ac0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c2a24)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (ffff8000108edcec)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (ffff8000108f334c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_irq_get
```
```
In drivers/ata/libata-acpi.c (ffff8000109b6244)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffff8000109c7b78)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffff800010a1a3a8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90e50)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab62d4)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/i2c-core-slave.c (ffff800010ab6628)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba598)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b97164)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b979a8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98bb8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9bc84)
Location: include/linux/acpi.h:38
Inline: True
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116d17)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff81560dc6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81569565)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff828dfbd3)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81586ec6)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81589175)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815951cc)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff815a1c06)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815d905b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff815da4ea)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/property.c (ffffffff815de073)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/pci_slot.c (ffffffff81603229)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/xen/pci.c (ffffffff81637247)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/tty/serdev/core.c (ffffffff8167f488)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8169d16d)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8176e685)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffffffff817785c0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff817a2c6a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8180611b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In kernel/irq/irqdomain.c (ffffffff81107a07)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff81551c16)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8155a3b5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff828d82a8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81575c92)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81577cb5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8158435c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff81590da6)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815c2c4b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff815c410a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c4e58)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/property.c (ffffffff815c96b3)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8167ab5d)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8174e4d5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffffffff81758370)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff81794aaa)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817cd89b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
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
In kernel/irq/irqdomain.c (ffffffff81114c07)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f936)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff815680d5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff828f2a5a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff81586d86)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff81589035)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8159570c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff815a2196)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815dc05b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff815dd78a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815de6c8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/property.c (ffffffff815e36c3)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/pci_slot.c (ffffffff81627969)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816390a2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff81664fc7)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/tty/serdev/core.c (ffffffff816ad868)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816cb3dd)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81742f9f)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8174326d)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff8179e47e)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffffffff817a8960)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff817df70a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818451cb)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81866b8e)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868afd)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186ac41)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff8186b3ca)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
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
In kernel/irq/irqdomain.c (ffffffff81120237)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In drivers/gpio/gpiolib.c (ffffffff81579796)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81581ff5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff828f7e74)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/pci-acpi.c (ffffffff815a1236)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/quirks.c (ffffffff815a34e5)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815afb8c)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-label.c (ffffffff815bc596)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff815f5f1b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/pci_irq.c (ffffffff815f764a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f8588)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/property.c (ffffffff815fd583)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/pci_slot.c (ffffffff81641819)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816533f2)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/xen/pci.c (ffffffff8167f577)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/tty/serdev/core.c (ffffffff816c7cc8)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816e58ad)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8175e3ef)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8175e6bd)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/ata/libata-acpi.c (ffffffff817b82fe)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
```
```
In drivers/spi/spi.c (ffffffff817c27f0)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_spi_add_resource
```
```
In drivers/usb/core/hub.c (ffffffff817f99fa)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f74b)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881e3e)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884bd1)
Location: include/linux/acpi.h:38
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff8188535a)
Location: include/linux/acpi.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
</details>
</li>
</ul>

## Differences
