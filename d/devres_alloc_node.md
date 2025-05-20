# Function: <code>devres_alloc_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154f690)
Location: drivers/base/devres.c:136
Inline: False
Direct callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__devm_request_region
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/memremap.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:devm_ioremap
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:pcim_iomap_table
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/reset/core.c:devm_reset_control_get
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_master
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/power/power_supply_core.c:devm_power_supply_register
  - drivers/power/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
  - drivers/leds/led-class.c:devm_led_classdev_register
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk.c:devm_clk_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/extcon.c:devm_extcon_dev_allocate
  - drivers/extcon/extcon.c:devm_extcon_dev_register
```
**Symbols:**

```
ffffffff8154f690-ffffffff8154f6d3: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1460)
Location: drivers/base/devres.c:136
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:component_match_add_release
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_master
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/power/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/power_supply_core.c:devm_power_supply_register
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff815a1460-ffffffff815a14a3: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815cfaf0)
Location: drivers/base/devres.c:137
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:component_match_add_release
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_master
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_info
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff815cfaf0-ffffffff815cfb33: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e44c0)
Location: drivers/base/devres.c:137
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:component_match_add_release
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/firmware_class.c:assign_firmware_buf
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_of_led_classdev_register
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff815e44c0-ffffffff815e4503: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164b790)
Location: drivers/base/devres.c:137
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - mm/hmm.c:hmm_devmem_add
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:component_match_add_release
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
  - drivers/base/firmware_class.c:assign_firmware_buf
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_of_led_classdev_register
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff8164b790-ffffffff8164b7d3: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81686d90)
Location: drivers/base/devres.c:141
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/dma/mapping.c:dmam_alloc_coherent
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - mm/hmm.c:hmm_devmem_add
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:component_match_add_release
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_of_led_classdev_register
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81686d90-ffffffff81686ddb: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a6a30)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:component_match_add_release
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_of_led_classdev_register
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff816a6a30-ffffffff816a6a7b: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816dfad0)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_of_led_classdev_register
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff816dfad0-ffffffff816dfb16: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81703d20)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81703d20-ffffffff81703d66: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817bdf00)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_np
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/phy_device.c:devm_phy_package_join
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - drivers/interconnect/core.c:devm_of_icc_get
  - net/devres.c:devm_register_netdev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff817bdf00-ffffffff817bdf50: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d2c50)
Location: drivers/base/devres.c:165
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_notifier_register
  - drivers/clk/clk.c:devm_clk_hw_get_clk
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi.c:__devm_spi_alloc_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size
  - drivers/net/phy/phy_device.c:devm_phy_package_join
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - drivers/interconnect/core.c:devm_of_icc_get
  - net/devres.c:devm_register_netdev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff817d2c50-ffffffff817d2ca0: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b6660)
Location: drivers/base/devres.c:165
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_np
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_notifier_register
  - drivers/clk/clk.c:devm_clk_hw_get_clk
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-mux.c:__devm_clk_hw_register_mux
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_bulk_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:__devm_spi_alloc_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size
  - drivers/net/phy/phy_device.c:devm_phy_package_join
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - drivers/interconnect/core.c:devm_of_icc_get
  - net/devres.c:devm_register_netdev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff817b6660-ffffffff817b66ac: devres_alloc_node (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108ef840)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/bus/vexpress-config.c:devm_regmap_init_vexpress_config
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_by_phandle
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_handle
  - drivers/of/platform.c:devm_of_platform_populate
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffff8000108ef840-ffff8000108ef8e4: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dd0c8)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:__devm_ioremap
  - drivers/bus/vexpress-config.c:devm_regmap_init_vexpress_config
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/of/platform.c:devm_of_platform_populate
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
  - sound/soc/soc-devres.c:devm_snd_dmaengine_pcm_register
  - sound/soc/soc-devres.c:devm_snd_soc_register_card
  - sound/soc/soc-devres.c:devm_snd_soc_register_component
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
c09dd0c8-c09dd128: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000988e90)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/of/platform.c:devm_of_platform_populate
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
c000000000988e90-c000000000988f28: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582196)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/of/platform.c:devm_of_platform_populate
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffe000582196-ffffffe00058220c: devres_alloc_node (STB_GLOBAL)
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
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c9470)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff816c9470-ffffffff816c94b6: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a47a0)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/irq/irq_sim.c:devm_irq_sim_init
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff816a47a0-ffffffff816a47e6: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f79e0)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff816f79e0-ffffffff816f7a26: devres_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712280)
Location: drivers/base/devres.c:149
Inline: False
Direct callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
  - kernel/reboot.c:devm_register_reboot_notifier
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/iomem.c:devm_memremap
  - mm/dmapool.c:dmam_pool_create
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
  - drivers/tty/serdev/core.c:devm_serdev_device_open
  - drivers/char/hw_random/core.c:devm_hwrng_register
  - drivers/base/component.c:__component_match_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
  - drivers/leds/led-triggers.c:devm_led_trigger_register
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81712280-ffffffff817122c6: devres_alloc_node (STB_GLOBAL)
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
