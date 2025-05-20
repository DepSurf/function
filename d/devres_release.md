# Function: <code>devres_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81550100)
Location: drivers/base/devres.c:393
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_put
  - drivers/regulator/devres.c:devm_regulator_unregister
  - drivers/regulator/devres.c:devm_regulator_unregister_supply_alias
  - drivers/regulator/devres.c:devm_regulator_unregister_notifier
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
```
**Symbols:**

```
ffffffff81550100-ffffffff81550140: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1f00)
Location: drivers/base/devres.c:393
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_remove
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
```
**Symbols:**

```
ffffffff815a1f00-ffffffff815a1f40: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815d0620)
Location: drivers/base/devres.c:394
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_remove
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
```
**Symbols:**

```
ffffffff815d0620-ffffffff815d0660: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4ce0)
Location: drivers/base/devres.c:394
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
```
**Symbols:**

```
ffffffff815e4ce0-ffffffff815e4d20: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164bfb0)
Location: drivers/base/devres.c:394
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
```
**Symbols:**

```
ffffffff8164bfb0-ffffffff8164bff2: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816875d0)
Location: drivers/base/devres.c:398
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff816875d0-ffffffff81687612: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a7620)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff816a7620-ffffffff816a7662: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816e0720)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff816e0720-ffffffff816e0769: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704940)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81704940-ffffffff81704989: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817beab0)
Location: drivers/base/devres.c:406
Inline: True
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff817beab0-ffffffff817beb05: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3980)
Location: drivers/base/devres.c:422
Inline: True
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff817d3980-ffffffff817d39d5: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b7390)
Location: drivers/base/devres.c:422
Inline: True
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff817b7390-ffffffff817b73e5: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840ebc)
Location: drivers/base/devres.c:415
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/video/backlight/backlight.c:devm_backlight_device_unregister
  - drivers/clk/clk-devres.c:devm_clk_put
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/regulator/devres.c:devm_regulator_unregister_notifier
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_put
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81840d80-ffffffff81840dd5: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8198423c)
Location: drivers/base/devres.c:415
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/video/backlight/backlight.c:devm_backlight_device_unregister
  - drivers/clk/clk-devres.c:devm_clk_put
  - drivers/clk/clkdev.c:devm_clk_release_clkdev
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/regulator/devres.c:devm_regulator_unregister_notifier
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_put
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_put
```
**Symbols:**

```
ffffffff819840c0-ffffffff8198412e: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af235c)
Location: drivers/base/devres.c:420
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/video/backlight/backlight.c:devm_backlight_device_unregister
  - drivers/clk/clk-devres.c:devm_clk_put
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/regulator/devres.c:devm_regulator_unregister_notifier
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_put
```
**Symbols:**

```
ffffffff81af21b0-ffffffff81af221e: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b4050c)
Location: drivers/base/devres.c:420
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/video/backlight/backlight.c:devm_backlight_device_unregister
  - drivers/clk/clk-devres.c:devm_clk_put
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/regulator/devres.c:devm_regulator_unregister_notifier
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_put
```
**Symbols:**

```
ffffffff81b40360-ffffffff81b403ce: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b983ac)
Location: drivers/base/devres.c:420
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/video/backlight/backlight.c:devm_backlight_device_unregister
  - drivers/clk/clk-devres.c:devm_clk_put
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/regulator/devres.c:devm_regulator_unregister_notifier
  - drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_put
```
**Symbols:**

```
ffffffff81b98200-ffffffff81b9826e: devres_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f0898)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffff8000108f0898-ffff8000108f0918: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09ddaa4)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
c09ddaa4-c09ddaf0: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989cf0)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/video/backlight/backlight.c:devm_backlight_device_unregister
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/net/phy/mdio_bus.c:devm_mdiobus_free
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/of/platform.c:devm_of_platform_depopulate
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
c000000000989cf0-c000000000989d90: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582cd0)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffe000582cd0-ffffffe000582d3a: devres_release (STB_GLOBAL)
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
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816ca090)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff816ca090-ffffffff816ca0d9: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a53c0)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff816a53c0-ffffffff816a5409: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f8600)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff816f8600-ffffffff816f8649: devres_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devres_release(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712ea0)
Location: drivers/base/devres.c:406
Inline: False
Direct callers:
  - kernel/resource.c:devm_release_resource
  - kernel/iomem.c:devm_memunmap
  - mm/dmapool.c:dmam_pool_destroy
  - drivers/pinctrl/core.c:devm_pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_put
  - drivers/gpio/gpiolib-devres.c:devm_gpio_free
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_put
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios
  - drivers/pwm/core.c:devm_pwm_put
  - drivers/clk/clk.c:devm_clk_hw_unregister
  - drivers/clk/clk.c:devm_clk_unregister
  - drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free
  - drivers/char/hw_random/core.c:devm_hwrng_unregister
  - drivers/base/core.c:devm_device_remove_groups
  - drivers/base/core.c:devm_device_remove_group
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy
  - drivers/hwmon/hwmon.c:devm_hwmon_device_unregister
  - drivers/leds/led-class.c:devm_led_classdev_unregister
  - drivers/mailbox/mailbox.c:devm_mbox_controller_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier_all
  - drivers/extcon/devres.c:devm_extcon_unregister_notifier
  - drivers/extcon/devres.c:devm_extcon_dev_unregister
  - drivers/extcon/devres.c:devm_extcon_dev_free
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81712ea0-ffffffff81712ee9: devres_release (STB_GLOBAL)
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
