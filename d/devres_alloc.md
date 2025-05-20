# Function: <code>devres_alloc</code>

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
In kernel/resource.c (ffffffff810864a6)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__devm_request_region
```
```
In kernel/irq/devres.c (ffffffff810dee5a)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_request_threaded_irq
  - kernel/irq/devres.c:devm_request_any_context_irq
```
```
In mm/dmapool.c (ffffffff811d94fe)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff81402d11)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:pcim_iomap_table
```
```
In lib/genalloc.c (ffffffff81407530)
Location: include/linux/device.h:616
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff8141c146)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_phy_get
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
```
```
In drivers/pinctrl/core.c (ffffffff8141e7c6)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/devres.c (ffffffff814239de)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpiod_get_index
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpio_request_one
```
```
In drivers/pwm/core.c (ffffffff8142cbd6)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
```
In drivers/pci/pci.c (ffffffff814380f5)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/video/backlight/backlight.c (ffffffff8146b7ab)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff814be8c6)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff814de896)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/regulator/devres.c:_devm_regulator_get
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register_notifier
```
```
In drivers/reset/core.c (ffffffff814df4d6)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_get
```
```
In drivers/char/hw_random/core.c (ffffffff8151af56)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/devres.c (ffffffff8154f876)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devm_get_free_pages
```
```
In drivers/base/dma-mapping.c (ffffffff8155da6e)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/base/firmware_class.c (ffffffff8155fba7)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/base/regmap/regmap.c (ffffffff81562501)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_attach_dev
  - drivers/base/regmap/regmap.c:__devm_regmap_init
```
```
In drivers/ata/libata-core.c (ffffffff815c9b19)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff815e91f6)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_master
```
```
In drivers/net/phy/mdio_bus.c (ffffffff815ed176)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff81620b16)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
```
```
In drivers/input/input.c (ffffffff81667a7e)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff81673bce)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_device_register
```
```
In drivers/power/power_supply_core.c (ffffffff8167f706)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:devm_power_supply_register
  - drivers/power/power_supply_core.c:devm_power_supply_register_no_ws
```
```
In drivers/hwmon/hwmon.c (ffffffff81682e6a)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
```
```
In drivers/leds/led-class.c (ffffffff816ce286)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register
```
```
In drivers/clk/clk-devres.c (ffffffff816e3b96)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clk.c (ffffffff816e8c06)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/devfreq/devfreq.c (ffffffff816ec2e6)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff816edc26)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/extcon.c (ffffffff816eef76)
Location: include/linux/device.h:616
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:devm_extcon_dev_allocate
  - drivers/extcon/extcon.c:devm_extcon_dev_register
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
In kernel/resource.c (ffffffff81089cab)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/irq/devres.c (ffffffff810e4888)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In mm/dmapool.c (ffffffff811f76be)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff8144abd7)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
```
```
In lib/genalloc.c (ffffffff8144f395)
Location: include/linux/device.h:620
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff8146536e)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81467476)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/devres.c (ffffffff8146d3ae)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib.c (ffffffff81470e96)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/pwm/core.c (ffffffff81477e86)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff81483d95)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/video/backlight/backlight.c (ffffffff814b9aeb)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff8150e5c6)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff8152fd06)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff81530416)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/char/hw_random/core.c (ffffffff8156dc86)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff81597bd4)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
```
```
In drivers/base/devres.c (ffffffff815a18f5)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/dma-mapping.c (ffffffff815b1cbe)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/base/firmware_class.c (ffffffff815b421e)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/base/regmap/regmap.c (ffffffff815b98ce)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c16f8)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff815e01cb)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff8162868d)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff81647796)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_master
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8164be16)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff81681a76)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff816c93a2)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff816d43ae)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_device_register
```
```
In drivers/power/power_supply_core.c (ffffffff816e0606)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff816e3b7e)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
```
```
In drivers/watchdog/watchdog_core.c (ffffffff816ebb96)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff81731346)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register
```
```
In drivers/leds/led-triggers.c (ffffffff81731c76)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/clk/clk-devres.c (ffffffff81747ed6)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clk.c (ffffffff8174d0c6)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/devfreq/devfreq.c (ffffffff817517ae)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81752b36)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff817546ce)
Location: include/linux/device.h:620
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
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
In kernel/resource.c (ffffffff8108ebfb)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/irq/devres.c (ffffffff810eb0f8)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In mm/dmapool.c (ffffffff8120806e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff81469597)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
```
```
In lib/genalloc.c (ffffffff8146dd55)
Location: include/linux/device.h:625
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff8148466e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81486766)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/devres.c (ffffffff8148f27e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib.c (ffffffff81493006)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/pwm/core.c (ffffffff814991e6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff814a54f5)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/video/backlight/backlight.c (ffffffff814dbaeb)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff815306f6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clk.c (ffffffff81535936)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/acpi-dma.c (ffffffff8153a726)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff8155c366)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff8155c9e6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/char/hw_random/core.c (ffffffff8159a346)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff815c5724)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
```
```
In drivers/base/devres.c (ffffffff815d0012)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/dma-mapping.c (ffffffff815e11ae)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/base/firmware_class.c (ffffffff815e34cb)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/base/regmap/regmap.c (ffffffff815e8c2e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815f0b38)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff8160ce6b)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff816592fd)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff81678886)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_master
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8167d546)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff816af7a6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff816f7382)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff8170408e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_device_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81710a76)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff8171470e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_info
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
```
```
In drivers/watchdog/watchdog_core.c (ffffffff8171cab6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff817642d6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register
```
```
In drivers/leds/led-triggers.c (ffffffff81764c46)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8177d57e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8177e926)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff81780c8e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
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
In kernel/resource.c (ffffffff8108bbbb)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/irq/devres.c (ffffffff810eaa5b)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In mm/dmapool.c (ffffffff8121376e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff8146ec87)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap
```
```
In lib/genalloc.c (ffffffff81473425)
Location: include/linux/device.h:625
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff8148dd5e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff8148f66e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/devres.c (ffffffff81498d5e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib.c (ffffffff8149c9b6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149f9f6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff814a32b6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff814ab5e6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d2576)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff814e76be)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff815437e6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clk.c (ffffffff81548cf6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/acpi-dma.c (ffffffff8154df36)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff81570e96)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff81571436)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/char/hw_random/core.c (ffffffff815ae326)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff815da6b4)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
```
```
In drivers/base/devres.c (ffffffff815e4b72)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/dma-mapping.c (ffffffff815f5d59)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/base/firmware_class.c (ffffffff815f7a55)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:assign_firmware_buf
```
```
In drivers/base/regmap/regmap.c (ffffffff815fd60e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81604c7b)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff81620f4b)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff8166dadd)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff8168cfd6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81692666)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff816c4996)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff8170d07e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff81719b12)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81728dc6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff8172cb4e)
Location: include/linux/device.h:625
Inline: True
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81734d26)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff81782aa6)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
```
In drivers/leds/led-triggers.c (ffffffff81783306)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8179c0ee)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8179d426)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff8179fa36)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff817a5a66)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
```
In net/ethernet/eth.c (ffffffff817fb97e)
Location: include/linux/device.h:625
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff8109293b)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810aef56)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff810f2fab)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In mm/dmapool.c (ffffffff8122e2ee)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff8149b067)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap
```
```
In lib/genalloc.c (ffffffff814a07b5)
Location: include/linux/device.h:622
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff814c9ebe)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff814cb7ce)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/devres.c (ffffffff814d704e)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib.c (ffffffff814dafa6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814de4a6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff814e2026)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff814ea806)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815129f6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff8151c1be)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff815a68f6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clk.c (ffffffff815ac256)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/acpi-dma.c (ffffffff815b1616)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff815d5136)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff815d57b6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/char/hw_random/core.c (ffffffff81614df6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff81641444)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
```
```
In drivers/base/core.c (ffffffff81641996)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff8164be42)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/dma-mapping.c (ffffffff8165dd19)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/base/firmware_class.c (ffffffff8165f9eb)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:assign_firmware_buf
```
```
In drivers/base/regmap/regmap.c (ffffffff816657be)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166d05b)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff8168976b)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff816d710d)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff816f69c6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff816fc476)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff81730b06)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff8177e2b7)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff8178ad82)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8179a546)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff8179e30e)
Location: include/linux/device.h:622
Inline: True
```
```
In drivers/watchdog/watchdog_core.c (ffffffff817a6996)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff817f8e56)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
```
In drivers/leds/led-triggers.c (ffffffff817f96c6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8181343e)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81814566)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff81816b86)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff8181cbe6)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
```
In net/ethernet/eth.c (ffffffff8187932e)
Location: include/linux/device.h:622
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810962e5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810b5d95)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff810fb365)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff8110c799)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/dma/mapping.c:dmam_alloc_coherent
```
```
In mm/dmapool.c (ffffffff81251125)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff814d02f7)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffff814d5945)
Location: include/linux/device.h:637
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff814fab05)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff814fc755)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/devres.c (ffffffff815061f5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpio_request_one
  - drivers/gpio/devres.c:devm_gpio_request
  - drivers/gpio/devres.c:devm_gpiod_get_array
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib.c (ffffffff8150bc55)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150d795)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff815113d5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff81519ca5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81547c35)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff81551e65)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff815de535)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clk.c (ffffffff815e41a5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/acpi-dma.c (ffffffff815e9a45)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff8160df35)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff8160e4d5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff81642ee5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff8164ea15)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff8167c58d)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
```
```
In drivers/base/core.c (ffffffff8167ccc5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff81687462)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff81699dd0)
Location: include/linux/device.h:637
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816a1175)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816a8ae7)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff816c5885)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff81712bc0)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff81731e65)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81739c15)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff8176f2f5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff817bf3db)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff817cbf82)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_device_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e19d5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff817e588e)
Location: include/linux/device.h:637
Inline: True
```
```
In drivers/watchdog/watchdog_core.c (ffffffff817ee3d5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff81842465)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
```
In drivers/leds/led-triggers.c (ffffffff81842cd5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8185d2e5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8185e425)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff81860b05)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff81866d05)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffff818cacf5)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff8109e655)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810bf025)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff81106b25)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff81117e95)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff812657d5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff814e4c27)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffff814ea455)
Location: include/linux/device.h:641
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff8150ebe5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81511055)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81520ad5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81521535)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81522ed5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff815269b5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff8152fa35)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155e3b5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff815696f5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff815f7d55)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clk.c (ffffffff815fe595)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff81602ee5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff81603f25)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff8162aa55)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff8162aff5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff81661125)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff8166cca5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff8169c09d)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/base/component.c:component_match_add_release
```
```
In drivers/base/core.c (ffffffff8169c655)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff816a7052)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba6b0)
Location: include/linux/device.h:641
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816c19e5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c96c7)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff816e6c75)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff81735070)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff81754855)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175d315)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff81793975)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff817e683b)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff817f3189)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180d0f5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff8181133e)
Location: include/linux/device.h:641
Inline: True
```
```
In drivers/watchdog/watchdog_core.c (ffffffff8181a2a5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff8186e385)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
```
In drivers/leds/led-triggers.c (ffffffff8186ed55)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/mailbox/mailbox.c (ffffffff81879c75)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187ac75)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8187c535)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8187de45)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff818802b5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff81886b95)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffff818f5dc5)
Location: include/linux/device.h:641
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810a2c05)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810c5135)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff811100e5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff811221f5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff812807e5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff815116a9)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffff815171ae)
Location: include/linux/device.h:644
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff8153d315)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff8153f665)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8154ebd5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8154fa15)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff815513c5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff81555e75)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff8155f195)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158e815)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff81599f95)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff81629c65)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff8162a8c5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff8162fda5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff816355b5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff81636935)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff8165e615)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff8165ed05)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff81697205)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816a2865)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff816d4ba6)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff816d53d5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff816e0133)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f4992)
Location: include/linux/device.h:644
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816fc6f5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81704903)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff817202f5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff817709f0)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff81790095)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffffffff817931c5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8179a8a5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff817d2285)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff81827264)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff81833e09)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183d625)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184ede5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff8185335f)
Location: include/linux/device.h:644
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff818555b5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/watchdog/watchdog_core.c (ffffffff8185c425)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff818b25a5)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
```
In drivers/leds/led-triggers.c (ffffffff818b3005)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/mailbox/mailbox.c (ffffffff818bf205)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0585)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffffffff818c6825)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818c8415)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff818ca835)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff818d1165)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffff81955445)
Location: include/linux/device.h:644
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810a91d5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810ce235)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff8111c365)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff8112e865)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff81290215)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff81532119)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffff81537bfe)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff8155e125)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81560505)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81570075)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81570f05)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81572985)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff815774b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff815802d5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815b0445)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff815bb3a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff8164b755)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff8164c385)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff81652355)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff816572d5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff816586a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff81680d85)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff816813f5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff816b9db5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816c5605)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff816f8a76)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff816f9185)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff81704373)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff81718d92)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81720aa5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81728c53)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff817445c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff81794a50)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff817b3c75)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffffffff817b6d15)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817be365)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff81803155)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff81858794)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff81865779)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186efc5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81880815)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff81884dcf)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81887015)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/watchdog/watchdog_core.c (ffffffff8188dfe5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff818e4ed5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (ffffffff818e5925)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/mailbox/mailbox.c (ffffffff818f1d85)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f3085)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffffffff818f8c25)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818fa8a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff818fcc85)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff81903565)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffff8198b8e5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810b06c5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810d8005)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff81128695)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff8113d1f5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff812c2e75)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff8159665b)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
```
```
In lib/genalloc.c (ffffffff8159c151)
Location: include/linux/device.h:173
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff81600ba5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81602975)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff816153a5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81616d65)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff8161c425)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff81625805)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81659635)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff81665265)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff816fa855)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff816fb345)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff817012d5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff81708515)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff81708c55)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff81731f05)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff81732535)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff8176da85)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81779de5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff817b1476)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff817b2055)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff817be7a3)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d4845)
Location: include/linux/device.h:173
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff817dcc55)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817e540b)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_np
```
```
In drivers/mfd/mfd-core.c (ffffffff81802025)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff81858c50)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff8187b355)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8187e6b5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/phy_device.c (ffffffff81884995)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_join
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81886a55)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff818d38e5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff81929ab2)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff81939175)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81942f81)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194ec25)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff81953caf)
Location: include/linux/device.h:173
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81956805)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff81959b65)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
```
In drivers/watchdog/watchdog_core.c (ffffffff8195cbe5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff819b7f85)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (ffffffff819b8995)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5615)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get
```
```
In drivers/mailbox/mailbox.c (ffffffff819c78b5)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8835)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9725)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
```
In drivers/devfreq/devfreq.c (ffffffff819cee05)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d1165)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff819d3925)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff819da905)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In drivers/interconnect/core.c (ffffffff819dbb65)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
```
```
In net/devres.c (ffffffff819dd72c)
Location: include/linux/device.h:173
Inline: True
Inline callers:
  - net/devres.c:devm_register_netdev
  - net/devres.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810abde5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810d2e65)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff81123fd5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff811378f4)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff812cec35)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff815b20eb)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
```
```
In lib/genalloc.c (ffffffff815b7ba1)
Location: include/linux/device.h:178
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff81625a95)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81627885)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81639615)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163d695)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff81642bf5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff8164b605)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81679a35)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff81685ef5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff81717205)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff81717c95)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff8171a175)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_notifier_register
  - drivers/clk/clk.c:devm_clk_hw_get_clk
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/clk/clk-divider.c (ffffffff81720045)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
```
```
In drivers/clk/clk-composite.c (ffffffff8172242e)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
```
```
In drivers/dma/dmaengine.c (ffffffff81725735)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff81725ea5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff8174e025)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff8174e685)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff81788465)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81794555)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff817c5dc6)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff817c6925)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/platform.c (ffffffff817d19db)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
```
In drivers/base/devres.c (ffffffff817d3503)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff817e9205)
Location: include/linux/device.h:178
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff817f1d15)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817fa34b)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode
```
```
In drivers/mfd/mfd-core.c (ffffffff81812ed5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff81868eb0)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff8188a005)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
  - drivers/spi/spi.c:__devm_spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8188cc25)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_devres.c (ffffffff8188d3c4)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size
```
```
In drivers/net/phy/phy_device.c (ffffffff818930c5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_join
```
```
In drivers/usb/phy/phy.c (ffffffff818ddc85)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff81931022)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81949361)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81954685)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff81958acf)
Location: include/linux/device.h:178
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8195a945)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff81960795)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81963695)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff819ba425)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (ffffffff819badf5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5845)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get
```
```
In drivers/mailbox/mailbox.c (ffffffff819c7805)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8585)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9265)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce985)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d0e25)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff819d34a5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff819d9795)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In drivers/interconnect/core.c (ffffffff819db265)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
```
```
In net/devres.c (ffffffff819dd12c)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - net/devres.c:devm_register_netdev
  - net/devres.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810ad4b7)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810d4b65)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff81124325)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff811386e4)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff812d5855)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff815bcf2b)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:devm_ioremap_np
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
```
```
In lib/genalloc.c (ffffffff815c2a11)
Location: include/linux/device.h:178
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff81609555)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff8160af95)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8161d265)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81621315)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff81625a15)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff8162e1e5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165c415)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff81668cf5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff816f84d5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff816f8f85)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff816fb475)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_notifier_register
  - drivers/clk/clk.c:devm_clk_hw_get_clk
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/clk/clk-divider.c (ffffffff81701285)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
```
```
In drivers/clk/clk-fixed-factor.c (ffffffff81701ee5)
Location: include/linux/device.h:178
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff81702c65)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__devm_clk_hw_register_mux
```
```
In drivers/clk/clk-composite.c (ffffffff8170383e)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
```
```
In drivers/dma/dmaengine.c (ffffffff817069d5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff81707735)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff81731ba5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff817321a5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_bulk_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff8176bdb5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81777225)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff817a8eb6)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff817a9de5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/platform.c (ffffffff817b540b)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
```
In drivers/base/devres.c (ffffffff817b6f13)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff817cd9d5)
Location: include/linux/device.h:178
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff817d65c5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817df06b)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode
```
```
In drivers/mfd/mfd-core.c (ffffffff817f75f5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff8184b8e0)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff8186b7c5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/spi/spi.c:__devm_spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8186ede5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_devres.c (ffffffff8186fd04)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size
```
```
In drivers/net/phy/phy_device.c (ffffffff81875555)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:devm_phy_package_join
```
```
In drivers/usb/phy/phy.c (ffffffff818c0fe5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff819142a2)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819384f5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff8193c53f)
Location: include/linux/device.h:178
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8193f655)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff81943ce5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81947ab5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff8199ec75)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (ffffffff8199f615)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819aa815)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get
```
```
In drivers/mailbox/mailbox.c (ffffffff819ac745)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad4d5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ae335)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
```
In drivers/devfreq/devfreq.c (ffffffff819b3ae5)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819b6095)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff819b8755)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff819bfa35)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In drivers/interconnect/core.c (ffffffff819c1515)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
```
```
In net/devres.c (ffffffff819c337c)
Location: include/linux/device.h:178
Inline: True
Inline callers:
  - net/devres.c:devm_register_netdev
  - net/devres.c:devm_alloc_etherdev_mqs
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100f60)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffff80001012dc00)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffff800010180a60)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffff800010193bf8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffff80001032cd18)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffff80001063d984)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffff800010644234)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/bus/vexpress-config.c (ffff800010685d38)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/bus/vexpress-config.c:devm_regmap_init_vexpress_config
```
```
In drivers/phy/phy-core.c (ffff800010686e2c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffff80001068cfa4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffff8000106c635c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffff8000106c70b4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffff8000106ca750)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffff8000106d8b84)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffff8000106e5a5c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071b104)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffff800010741b10)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffff8000107ba18c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffff8000107bb0cc)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffff8000107c1c54)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffff8000107fd714)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffff8000107ff25c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffff80001084aaa8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/regulator/of_regulator.c (ffff80001084b884)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/reset/core.c (ffff80001084ce14)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffff8000108aa078)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffff8000108b76f8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffff8000108e2828)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffff8000108e3320)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffff8000108eff58)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffff80001090c198)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffff8000109151b0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091e588)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffff80001094077c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffff80001099f25c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/ata/libahci_platform.c (ffff8000109bd3a0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/spi/spi.c (ffff8000109c7f08)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffff8000109cab14)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (ffff8000109d7698)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffff800010a38588)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffff800010a974d8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffff800010aa6b10)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab29f0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc4dc)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffff800010ad1b38)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffff800010ad5340)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/thermal/of-thermal.c (ffff800010ad9b44)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
```
```
In drivers/watchdog/watchdog_core.c (ffff800010adeb28)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffff800010b49d54)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (ffff800010b4aa10)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/firmware/ti_sci.c (ffff800010b50bf8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_by_phandle
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_handle
```
```
In drivers/of/platform.c (ffff800010b6df98)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/of/platform.c:devm_of_platform_populate
```
```
In drivers/mailbox/mailbox.c (ffff800010b79e60)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7ec90)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffff800010b858f4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffff800010b87260)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffff800010b8a140)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffff800010b9f710)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffff800010c368b4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (c035d28c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (c037da88)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (c03d0848)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (c03e0f70)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (c0543120)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (c07e3e64)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (c07ea9c0)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/bus/vexpress-config.c (c0829bf0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/bus/vexpress-config.c:devm_regmap_init_vexpress_config
```
```
In drivers/phy/phy-core.c (c082ab14)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (c082f048)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (c086430c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (c0864a48)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/pwm/core.c (c087541c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (c087eba0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (c08a4f38)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (c08c6574)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (c08e63ec)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (c08e6fb4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (c08ec7f8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (c091ed0c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/regulator/devres.c (c0953fd8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/regulator/of_regulator.c (c0954e60)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/reset/core.c (c0959288)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (c09a6534)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (c09b136c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (c09d150c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (c09d1dc0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (c09dd748)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (c09f55ac)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/base/regmap/regmap.c (c09fb1d8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (c0a03994)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (c0a29df0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (c0a6f928)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/ata/libahci_platform.c (c0a881b0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/spi/spi.c (c0ab0e90)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (c0ab3fa4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (c0abf228)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (c0b0a9a8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (c0b7a5e4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (c0b8562c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (c0b94034)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (c0bad420)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (c0bb28b4)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (c0bb509c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/thermal/of-thermal.c (c0bb9db0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
```
```
In drivers/watchdog/watchdog_core.c (c0bc0624)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (c0c33190)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (c0c33a8c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/of/platform.c (c0c50e0c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/of/platform.c:devm_of_platform_populate
```
```
In drivers/mailbox/mailbox.c (c0c5f858)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c62908)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (c0c68680)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (c0c6a150)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (c0c6e47c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (c0c813e4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In sound/soc/soc-jack.c (c0cad9dc)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
```
```
In sound/soc/soc-devres.c (c0cb595c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - sound/soc/soc-devres.c:devm_snd_dmaengine_pcm_register
  - sound/soc/soc-devres.c:devm_snd_soc_register_card
  - sound/soc/soc-devres.c:devm_snd_soc_register_component
```
```
In net/ethernet/eth.c (c0d49248)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (c0000000001484c4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (c000000000176a7c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (c0000000001db6b8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (c0000000001f3e94)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (c000000000404d84)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (c0000000007e7b60)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (c0000000007f07e0)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/phy/phy-core.c (c000000000823430)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (c000000000826880)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (c0000000008430dc)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (c000000000843cf0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/pwm/core.c (c00000000084f95c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (c00000000085c92c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088c84c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (c0000000008a2748)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/dma/dmaengine.c (c0000000008c8a38)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/regulator/devres.c (c0000000008e84d8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/regulator/of_regulator.c (c0000000008e96f8)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/reset/core.c (c0000000008ebefc)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (c000000000940a2c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (c000000000951e5c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (c000000000977400)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (c0000000009781ac)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (c0000000009896e4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (c0000000009abf40)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/base/regmap/regmap.c (c0000000009b7578)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c34d8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (c0000000009e91ac)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (c000000000a63890)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (c000000000a88b1c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (c000000000a8d22c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (c000000000a996d8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (c000000000af5e60)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (c000000000b78050)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (c000000000b881d4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (c000000000b9638c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (c000000000baf11c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (c000000000bb6868)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (c000000000bbb0b4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/thermal/of-thermal.c (c000000000bc11b0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
```
```
In drivers/watchdog/watchdog_core.c (c000000000bc65fc)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (c000000000c3e54c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (c000000000c3fa28)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/of/platform.c (c000000000c487d4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/of/platform.c:devm_of_platform_populate
```
```
In drivers/mailbox/mailbox.c (c000000000c58e9c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a8b8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (c000000000c636b0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (c000000000c66108)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (c000000000c69c60)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (c000000000c730a8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (c000000000d2e9f0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffe0000c828c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffe0000e1cc6)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffe0001189ec)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffe000125f8e)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffe00022b9a2)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffe00046b6ea)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffe0004710d4)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffe0004967d0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffe0004991a6)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffffffe0004aa452)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffffffe0004aab34)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/pwm/core.c (ffffffe0004b1ac0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffe0004ba66a)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e30b8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/clk/clk-devres.c (ffffffe000509362)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffe000509fba)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffe00050f8e2)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffe000517308)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/regulator/devres.c (ffffffe00052a708)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/regulator/of_regulator.c (ffffffe00052b2de)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/reset/core.c (ffffffe00052c62c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffe00055eba2)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffe0005683dc)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffe000577e1e)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffe000578716)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffe0005827a0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/regmap/regmap.c (ffffffe0005964c2)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059dc00)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b4094)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffe0005ff0e6)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffe00061859a)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffffffe00061a428)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (ffffffe0006237d8)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffe0006545ba)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffe0006a8a42)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffe0006b2fc2)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006ba648)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c9c86)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffe0006ce466)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffe0006d0488)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/thermal/of-thermal.c (ffffffe0006d4168)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
```
```
In drivers/watchdog/watchdog_core.c (ffffffe0006d6bc4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffe00071d2d2)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (ffffffe00071dbee)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/of/platform.c (ffffffe00072293e)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/of/platform.c:devm_of_platform_populate
```
```
In drivers/mailbox/mailbox.c (ffffffe00072bcd6)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072cc94)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffffffe00072ebb0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffe000730134)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffe00073256c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffe00073793c)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffe0007a82e2)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810a2af5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810c85b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff81114945)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff81126e45)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff812887f5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff8152a6f9)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffff815301de)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff81556715)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81558af5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81565835)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff815666c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81568145)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff8156c2c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff815747f5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3c05)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff815af4f5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff816117b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff816123e5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff816183b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff8161d175)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff8161e545)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff81646805)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff81646e75)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff8167f815)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff8168b055)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff816be266)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff816be975)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff816c9ac3)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff816df0c2)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816e6dd5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816eea33)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff81702665)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff81759b60)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff81778755)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8177b7f5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81782e35)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff817bb535)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff8180d7a4)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff81818429)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81828d85)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff8182ac4f)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8182ce95)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81833e65)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-triggers.c (ffffffff81888ab5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/mailbox/mailbox.c (ffffffff818930b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818943b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffffffff81899f55)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8189bbd5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff8189dfb5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff818a2995)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffff8192b755)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810914d5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810b6dd5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff81105655)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/irq/irq_sim.c (ffffffff81108b55)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_sim_init
```
```
In kernel/dma/mapping.c (ffffffff811198a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff8127a645)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff8151a9d9)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffff815204be)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff81546bd5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81548fb5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81556685)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81557515)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81558f95)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pci/pci.c (ffffffff81562f55)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81592da5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff8159e685)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff81605d05)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff81606935)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff8160c8e5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff81611865)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff81612c35)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff81626c65)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff816272d5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/char/hw_random/core.c (ffffffff81668a55)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff81699516)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff81699c25)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff816a4df3)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff816b9702)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816c1415)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c9073)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff816d6475)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff81739a00)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff81758505)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8175b5a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81762bc5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/input/input.c (ffffffff817d4f14)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff817dfb19)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817f0415)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff817f22df)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4525)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/watchdog/watchdog_core.c (ffffffff817fb4f5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-triggers.c (ffffffff81840435)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/mailbox/mailbox.c (ffffffff8184b5b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184cad5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffffffff81857425)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818590a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/nvmem/core.c (ffffffff8185e105)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffff818e5505)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810a2aa5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810c7ae5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff81112835)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff81124d35)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff81286605)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff81526789)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffff8152bf1e)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff81552455)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff81554835)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffffffff815643a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81565235)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81566cb5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff8156b205)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff81574025)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a4195)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff815afa85)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff8163f595)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff816401c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff81646195)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff8164b115)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff8164c4e5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff81674bc5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff81675235)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff816adbf5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816b92c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff816ec736)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff816ece45)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff816f8033)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170ca52)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81713f65)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8171c113)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff81737a85)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff817898d0)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff817a8af5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffffffff817abb95)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817b31e5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff817f7fd5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff8184c924)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff81859909)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81863155)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81875cc5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff8187a27f)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8187c4c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81883495)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff818d9d35)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (ffffffff818da785)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/mailbox/mailbox.c (ffffffff818e6bb5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e7eb5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffffffff818e9645)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818eb2c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff818ed6a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff818f3f85)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffff8197c8e5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
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
In kernel/resource.c (ffffffff810aab25)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/resource.c:__devm_request_region
  - kernel/resource.c:devm_request_resource
```
```
In kernel/reboot.c (ffffffff810cffd5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_reboot_notifier
```
```
In kernel/irq/devres.c (ffffffff8111de55)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_setup_generic_chip
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/devres.c:devm_request_any_context_irq
  - kernel/irq/devres.c:devm_request_threaded_irq
```
```
In kernel/dma/mapping.c (ffffffff81131375)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
```
```
In mm/dmapool.c (ffffffff812963f5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - mm/dmapool.c:dmam_pool_create
```
```
In lib/devres.c (ffffffff81540109)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_table
  - lib/devres.c:devm_ioport_map
  - lib/devres.c:__devm_ioremap
```
```
In lib/genalloc.c (ffffffff81545d1e)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff8156c2e5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__devm_of_phy_provider_register
  - drivers/phy/phy-core.c:devm_phy_create
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:devm_of_phy_get
  - drivers/phy/phy-core.c:devm_phy_get
```
```
In drivers/pinctrl/core.c (ffffffff8156e6c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register_and_init
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8157e2c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8157f155)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request_one
  - drivers/gpio/gpiolib-devres.c:devm_gpio_request
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81580bd5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
```
In drivers/pwm/core.c (ffffffff81585705)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
```
```
In drivers/pci/pci.c (ffffffff8158e505)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:pcim_enable_device
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815be595)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create
```
```
In drivers/video/backlight/backlight.c (ffffffff815c94f5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_backlight_device_register
```
```
In drivers/clk/clk-devres.c (ffffffff816598e5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_get_clk_from_child
  - drivers/clk/clk-devres.c:devm_clk_bulk_get_all
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
  - drivers/clk/clk-devres.c:devm_clk_get
```
```
In drivers/clk/clkdev.c (ffffffff8165a515)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:devm_clk_hw_register_clkdev
```
```
In drivers/clk/clk.c (ffffffff81660725)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff816656b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaenginem_async_device_register
```
```
In drivers/dma/acpi-dma.c (ffffffff81666a85)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register
```
```
In drivers/regulator/devres.c (ffffffff8168f225)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/regulator/devres.c:devm_regulator_register_notifier
  - drivers/regulator/devres.c:devm_regulator_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_register
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_get
```
```
In drivers/reset/core.c (ffffffff8168f895)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:devm_reset_controller_register
```
```
In drivers/tty/serdev/core.c (ffffffff816c8055)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816d3895)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:devm_hwrng_register
```
```
In drivers/base/component.c (ffffffff81706f76)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/component.c:__component_match_add
```
```
In drivers/base/core.c (ffffffff81707685)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/core.c:devm_device_add_group
```
```
In drivers/base/devres.c (ffffffff817128d3)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_add_action
```
```
In drivers/base/firmware_loader/main.c (ffffffff81727552)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff8172f155)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__devm_regmap_init
  - drivers/base/regmap/regmap.c:regmap_attach_dev
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81737473)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
```
```
In drivers/mfd/mfd-core.c (ffffffff81752ec5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
```
In drivers/ata/libata-core.c (ffffffff817a3720)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff817c2985)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
```
In drivers/spi/spi-mem.c (ffffffff817c5b25)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817cd195)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size
```
```
In drivers/usb/phy/phy.c (ffffffff81812215)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_get_phy
```
```
In drivers/input/input.c (ffffffff81867c14)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:devm_input_allocate_device
```
```
In drivers/rtc/class.c (ffffffff818749e9)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187e3b5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81891665)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws
  - drivers/power/supply/power_supply_core.c:devm_power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff81895c7f)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81897ef5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
```
```
In drivers/watchdog/watchdog_core.c (ffffffff8189ef55)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:devm_watchdog_register_device
```
```
In drivers/leds/led-class.c (ffffffff818f6855)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_register_ext
```
```
In drivers/leds/led-triggers.c (ffffffff818f72a5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:devm_led_trigger_register
```
```
In drivers/mailbox/mailbox.c (ffffffff81903835)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904bd5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8190a6c5)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8190c345)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev
```
```
In drivers/extcon/devres.c (ffffffff8190e725)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier_all
  - drivers/extcon/devres.c:devm_extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_register
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
```
In drivers/nvmem/core.c (ffffffff81915025)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:devm_nvmem_register
```
```
In net/ethernet/eth.c (ffffffff8199ee35)
Location: include/linux/device.h:880
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
</details>
</li>
</ul>

## Differences
